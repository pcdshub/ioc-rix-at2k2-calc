ioc-rix-at2k2-calc IOC Startup Scripts
=====================================================

RIX AT2K2 solid attenuator calculator IOC startup script.

config.sh
---------

The IOC configuration settings are primarily in this file.

initialize.sh
-------------

This script creates the environment necessary to run the IOC.

activate\_env.sh
----------------

Use this script to activate the conda environment previously built by
``initialize.sh``.

st.cmd
------

This is the {bash, procserv, IocManager}-compatible entry point
for starting the IOC.
