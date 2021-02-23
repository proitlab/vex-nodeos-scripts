# vex-nodeos-scripts
Script to safely running Vexanium nodeos

Default command to run nodeos in Vexanium network is unsecure because it show private key.

Reference to: https://belajar.vexanium.com/article/command-umum-blockproducer/


This is just simple bash script to easily manage Vexanium nodeos by utilizing config.ini

## Features

- Enforce user to not using superuser/root to run the command
- Utilizing config.ini for better security (Hide the private key)
- Kill nodeos gracefully to prevent data block corrupt
- List current available mainnet for better peering nodes

## Step by Step

1. git clone https://github.com/proitlab/vex-nodeos-scripts
2. cp vex-nodeos-scripts/* .
3. Edit config.ini
4. ./startnode.ds
5. ./checknode.ds

## Starting Node 

    ./startnode.ds 


## Stopping Node

    ./killnode.ds


## Checking Node

    ./checknode.ds
