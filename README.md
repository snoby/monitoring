Monitoring
=========

This role will deploy ca advisor and node exporter as systemd units

[![Build Status](https://drone.mattsnoby.com/api/badges/snoby/monitoring/status.svg)](https://drone.mattsnoby.com/snoby/monitoring)

Testing
=======
Testing can be done with drone with 'drone exec' or look at the .drone.yml file for how to run the molecule commands for testing.


To run locally you need python packages:
ansible molecule molecule-docker ansible-lint yamllint