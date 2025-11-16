# ![The ORC_CDMX Project](../docs/images/ORC-IGEF.png "Red Pitaya Project") The ACQUA suite

Only a few libraries are needed to compile and operate  ACQUA v1 suite. In the Ubuntu 22.04 version of the OS installed on the Red Pitaya board, just run this command:

```bash
apt update
apt upgrade
apt install i2c-tools libi2c-dev python-smbus build-essential screen rsync
cd src/
make
```

and that's it. If everything was fine, you will find a binary file called **orc_cu** in the current directory. 

For further information, including the installation of the OS image of the SD card, please check the ACQUA resources section in the [project wiki](https://redpitaya.com/?srsltid=AfmBOopNwSPrcAQIWzPvTa2CkRww0IPlgAuIu8vFdraHP_bxXWKgq1h3).

## About ORC

The [ (ORC-CDMX)](https://www.geofisica.unam.mx/observatorios/rayos_cosmicos/grupo_raycos/historiaobservatoriocu.html) is a cosmic rays Observatory at UNAM. 
