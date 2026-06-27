# Solar Panel Tracking System

## Project Overview

This project automatically tracks the brightest light source using two LDR sensors and a servo motor.

## Objective

To maximize solar energy collection by automatically orienting the solar panel toward the strongest light source.

## Components Used

- Arduino Uno
- 2 LDR Sensors
- Servo Motor
- Jumper Wires
- Wokwi Simulator

## Software Used

- Arduino IDE
- Wokwi
- Embedded C

## Working Principle

Two LDR sensors continuously detect light intensity.

The Arduino compares both sensor values.

If the left LDR detects more light, the servo rotates left.

If the right LDR detects more light, the servo rotates right.

When both sensors detect similar light intensity, the servo stops.

## Features

- Automatic light tracking
- Single-axis tracking
- Servo motor control
- Real-time sensor monitoring

## Future Improvements

- Dual-axis tracking
- ESP32 Wi-Fi monitoring
- IoT dashboard

## Wokwi Simulation Link

https://wokwi.com/projects/465546999256296449
