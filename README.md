# GitLab-Runner role with support for the use of HPC image-based deployments including options for Jacamar 

Structure:

README.md  # this file

./files:
validate_user.sh  # user validation script for use with Jacamar-auth

./tasks:
main.yml  # configuration tasks

./templates:
config.toml.j2  # config for all runners
custom-config.toml.j2  # config for each custom executor (Jacamar)
