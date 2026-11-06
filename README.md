# NexaDrop: IV Fluid Monitoring and Alerting System

An IoT system that watches the fluid level of an IV bag and alerts caregivers before it runs low, replacing error-prone manual checking.

## How it works
- **Load cell + HX711** measure the bag's weight, which maps to remaining fluid
- **ESP8266 (ESP-01 Wi-Fi)** processes the data, shows it on a local **LCD** and sends alerts below a threshold
- **DHT11** monitors room temperature and humidity
- **Sound sensor** lets the patient call for help by clapping twice

## Tech
ESP8266, HX711 load cell, DHT11, sound sensor, LCD, Wi-Fi/IoT

## Contents
`NexaDrop - IV Fluid Monitoring And Alerting System.pdf`: full report (abstract, background, method, results, conclusion)

## Authors
Vishmini Michel and group members.
