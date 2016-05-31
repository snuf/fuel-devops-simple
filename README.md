# Fuel Devops Simple

## Description
A simple way to deploy https://github.com/openstack/fuel-devops with some
assumptions regarding the setup. It is an attempt to automate fuel-dev 
setup and installation:
https://docs.fuel-infra.org/fuel-dev/devops.html

## Requirements
* Ubuntu (15.x or 16.x)
* A Fuel ISO, either 7.0 or 8.0

## Other perks
The script also allows for daisy chaining, where fuel-devops-simple is used
to create the environment after which fuel-devops-simple launches a
complimentary script to fill in the required bits for the specific use case.
see fuel-devops-datera as an example.
The settings-<version> is copied in automatically for fuel_qa/fuelweb_test
The settings.py file is copied in for the fuel-devops-venv
