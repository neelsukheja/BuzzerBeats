
# Doorbell Project with Arduino Uno

## Overview

This Arduino Uno project is a basic doorbell system that uses a switch to trigger a buzzer. When the switch is pressed, the buzzer plays a short melody.

## Components

- Arduino Uno
- Buzzer
- Switch/Button
- Jumper wires 

## Wiring

- Connect the switch to pin 8 on the Arduino Uno.
- Connect the buzzer to pin 12 on the Arduino Uno.

## Usage

1. Upload the provided Arduino sketch to your Arduino Uno board.
2. Press the switch to activate the doorbell.
3. The buzzer will play a short melody.

## Code Details

- `plugkey`: Pin connected to the switch.
- `buzzer`: Pin connected to the buzzer.
- `switchread`: Variable to store the switch state.
- `prev`: Variable to track the previous switch state.
- `dt`: Delay time between switch state checks.
- `dt1`: Delay time for the buzzer melody.

## Melody Details

The buzzer plays a simple melody when the switch is pressed. The melody consists of alternating high and low states with specified delay times (`dt1`).

## Acknowledgments

- Original code by Neel Sukheja
- Inspiration from Arduino community projects
