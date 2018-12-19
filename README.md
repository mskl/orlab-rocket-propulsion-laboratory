# Orlab Rocket Propulsion Laboratory (ORPL)

## Main goal:
The main goal of this project is to create hybrid rocket engine with thrust vectoring and oxidizer (thrust) regulation. The ultimate goal is to replicate the SpaceX GrassHopper lander in the low scale. And have fun.

***
## Main challenges:
### Testbed design
It is necessary to create an enviroment where we can test the rocket motors withou worrying about the personal safety. 

#### Basic testbed design requirements
It would be the best if the thrurster was usable in the horizontal and in the vertical orientation as well.
1. Thrust logging
    - Arduino + SD card slot / Ethernet connection + load cells + GoPro
2. Safety barrier
    - Plywood structure + sand filling?
3. Remote oxidizer control
    - The oxidizer tank has a that is far away and a reverse fire protection mechanism near the testbed to prevent reverse fire of the oxidizer.
    - Reductution valve to maintain the pressure


#### Pretest precautions
It is vital to make sure that the chamber and the tubing does not contain any burnable particles that might trigger an explosion when mixed with the oxidizer.

#### Test protocol
- date + time
- summary
- video footage
- thrust force data from Arduino -> plotted
- conclusion (what we found out)

### Hybrid motor design
1. Outer shell
    - light
    - not burnable
    - insulating

2. Nozzle design
    - maximum thrust at sea level

3. Oxidizer inlet (atomizer)
    - disperse the oxidizer to be spread evenly in the fuel

### Fuel selection
1. Naive - PVC tube
    - easy to obtain
    - might move inside the chamber

2. Rubber
    - high density
    - stable in the chamber
    - insulating

3. Wax
    - easy to prepare
    - cheap
    - will drip out while tests
    - different scores when horizontal and vertical?

### Oxidizer selection
1. O2 - liquid oxygen
    - cheap
    - high pressure

2. NO2 - nitrous oxide
    - expensive
    - lower pressure
    - more stable?

### Thrust vector control
How to control the vectoring of the engine?

#### Motor types
- Servo motor
    - cheap
    - light
    - plastic so it melts
- Stepper motor
    - expensive
    - heavy
- Electromagnetic coil
    - cheap
    - light   
    - cannot control the vector precisely
    - requires more HW
    - harder to make
    - earth magnets stop working at high temperature

#### Gimbal types
1. Whole motor
Move the whole rocket motor changer alog with the thurster.
    - requires space in the fuselage
    - requires flexible top nozzle
    - the motor mounts need to be flexible
    - the motor actuator mounts need to be fire resistant (servo horns would probably melt)

2. Nozzle only
The nozzle is moved individually around the fixed motor chamber.
- engineering challenge to seal the gap between the burn chamber and a nozzle

### Oxidizer regulation
Selecting the correct electronic oxidizer control valve that is:
- suitable pressure
- light
- cheap

### Engine ignition
The hybrid rocket engine might require high ignition temperature.
- Sparklers - for testing purposes?
- Electronic sparkler - for remote triggering?

***
## Price prerequisities
It is necessary to obtain the oxidizer source and a way to control it in the test enviroment. The testbed design is not compulsory but should not be overlooked.
| material                                  | CZK       |
|-------------------------------------------|-----------|
| oxidizer tank + oxidizer                  |~2k max    |
| oxidizer control valve                    |~1k max    |
| steel / aluminium mounts + motor clamp    |~1k        |
| plywood / material for the testbed        |           |
| electronic control valve                  |~1.6k      |
| plumbing - hoses for oxidizer             |           |