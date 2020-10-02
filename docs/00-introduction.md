# Introduction

This document will describe the high-level architecture of my IoT setup.

## Transmission
All collected measurements are transmitted over MQTT to Mosquitto.
The measurements are received by Node-RED and forwarded to the database.

## Database
All measurements are stored in InfluxDB.

## Visualisation
Some measurements are visualised with Grafana.
