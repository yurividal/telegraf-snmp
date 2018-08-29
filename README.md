# Telegraf Docker Image with Net-SNMP

Telegraf is an agent for collecting metrics and writing them to InfluxDB or other outputs. This is a modification to the excellent work done by [nuntz](https://github.com/nuntz/telegraf-snmp). The reason why he created this repository ([Docker Hub link](https://hub.docker.com/r/nuntz/telegraf-snmp/)) is that the official one does not include the SNMP tools, necessary for the `input.snmp` input plugin.


Based on:

* https://github.com/influxdata/influxdata-docker
* https://github.com/weldpua2008/docker-net-snmp
* https://github.com/influxdata/influxdata-docker
* https://github.com/adityapandurangi/telegraf-snmp-unifi
