# Open Ondemand Desktop app for Hábrók

This repository contains the settings for the Open Ondemand desktop
app for the Hábrók cluster of the University of Groningen.

These files need to be placed inside: `/etc/ood/config/apps/bc_desktop`.
The other definitions for the desktop app are in `/var/www/ood/apps/sys/bc_desktop`.
The latter have not been modified.

The files are based on the instructions at https://osc.github.io/ood-documentation/latest/enable-desktops.html
the files in this repository are modified versions from the files in the installation.

The file `login1.yml` contains the settings for our cluster. The name is derived from the main login node
which appears as a cluster in the configuration.

The file `submit/submit.yml.erb` contains the parameters for the job submission of the desktop session job.

The files are licensed under the same MIT license as used for Open Ondemand itself.
