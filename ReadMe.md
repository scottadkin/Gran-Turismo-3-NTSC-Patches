## Various Gran Turismo 3 NTSC Patches

## New Patches
After learning how to properly do the newer patches I will most likely be adding all cheats into a single file, as you can toggle on and off what cheats you want to use. You can find the new patch file in the current directory **[8AA991B0.pnach](https://github.com/scottadkin/Gran-Turismo-3-NTSC-Patches/blob/main/8AA991B0.pnach)**.

## Old Patches
These are the old format non-toggleable patches:
- Patches placed in the **AllRaces** folder are for single race events, championship events, rally events, and Endurance events. Many will work in arcade mode and license tests as well, like the power modifier cheats.
- Patches placed in the **Arcade**,**LicenseTests**,**ChampionshipRaces**,**Single Races** folder only affects those events.
- Patches placed in the **Like The Wind** folder are made specifically for that event and cars in it and may cause issues in any other event.


## New Patch Cheats

### Remove AI Rubberband(Simulation Mode & Arcade Races)
- Removes the rubberband from AI cars, they will no longer slow down if you fall behind, and they won't speed up if you are far ahead. Not all events use this feature but it's heavily used in the beginner league, and pretty much not used at all by the professional league.
- **Change before a race start for the changes to take effect. Patch relies on checking if a race is a single event or a championship event by checking if the race tick counter has hit 1 for either single race events or championship events.**

### Remove AI Max Throttle Handicaps(Simulation Mode & Arcade Races)
- Removes the Max Throttle limits from AI cars. Not all events use this feature but it's heavily used in the beginner league, and pretty much not used at all by the professional league.
- **Change before a race start for the changes to take effect. Patch relies on checking if a race is a single event or a championship event by checking if the race tick counter has hit 1 for either single race events or championship events.**

### Crazy Grass/Dirt/Sand Physics
- Gives Grass/Dirt/Sand bizarre physics affecting all cars including AI.
- The AI auto drive in license tests now automatically gets given normal values to prevent fails before the test has even started. Seattle is still impossible to complete when enabled.
- Includes another cheat to set the value back to normal.
- **Change at any point for the changes to take effect.**

### Angry Walls
- Walls will push you back a lot harder once hit, affecting all cars including AI.
- The AI auto drive in license tests now automatically gets given normal values to prevent fails before the test has even started. 
- Includes another cheat to set the value back to normal.
- **Change at any point for the changes to take effect.**
- **Can cause game crashes when you or the AI get thrown out of the track, be sure to have save states to prevent progress loss**

### Gravity Cheats
- Change the gravity value of the game.
- Earth
- Sun
- Moon
- Jupiter
- Zero Gravity
- **Change in any menu, will not take effect if you change mid race.**

### Air Resistance Modifier Cheats
- You can scale all cars' downforce and drag values.
- This affects all cars including AI.
- 0x(No downforce or drag), 1x(normal), 2x(double all values), 3x,4x,5x,8x,10x
- **Change in any menu, will not take effect if you change mid race.**


### Crazy Kerbs For Simulation Mode Races
- Makes the kerbs unusable, normally ending up with throwing your car in a random direction.
- Wet kerbs are unaffected.
- **Change before a race start for the changes to take effect. Patch relies on checking if a race is a single event or a championship event by checking if the race tick counter has hit 1 for either single race events or championship events.**

### Crazy Kerbs 3 For License Tests
- Makes the kerbs unusable, normally ending up with throwing your car in a random direction.
- The AI auto drive in license tests now automatically gets given normal values to prevent fails before the test has even started. 
- Seattle tests IB-3 And S-2 Now have different values to allow going over the tram tracks without it being a fail 100% of the time.
- Wet kerbs are unaffected.
- **Change at any point for the changes to take effect.**

### Global Power Multipliers
- Adjust all cars' power and upgrades including AI.
- Some Examples: 0.10x, 0.25x, 0.5x, 1.25x, 1.50x, 1.75x, 2x, 5x, 10x, 25x, 50x, 100x, and even up to 1 million times power.
- **Change in any menu, will not take effect if you change mid race.**

### RPM Limit Changers
- Set your cars make RPM to 17000 in simulation mode, single races and championship races. Hud changes most of the time to the new RPM limit.

### Global Grip Multipliers
- Adjust all cars' grip including AI.
- Higher values can cause unusual physics.
- Some Examples: 50%, 100%, 125%, 150%, 200%, 300%, 500%, 750%, 1000%
- **Change in any menu, will not take effect if you change mid race.**


## Notes

### Event ticks
- Single race ticks **1F978FC** 
- Championship race ticks **1F9685C**
- License test ticks **1FD0D0C** 
- Machine test ticks **1FB728C**
- Home -> test run ticks **1FC55BC**  
- Arcade Race Ticks **21FAC35C**

### Track Ids address?
Address = 209C41D2 2 bytes

- 100M Circle(A5) = 118
- 100M Circle Wet(IB2) = 118
- 60M Circle(A4) = 120
- 60M Circle Wet(IB1) = 117
- Apricot Hill = 1040
- Apricot Hill(S1) = 1042
- Apricot Hill(IB8) = 1050
- Apricot Hill Reverse = 1037
- Complex String = 473
- Complex String(IB6, IB7, IA8) = 471
- Complex String(IA7) = 470
- Deep Forest = 1032
- Deep Forest(B3,B4 Tests) = 998
- Deep Forest(B7 Test,IA3) = 999
- Deep Forest Reverse = 981
- Grand Valley = 1127
- Grand Valley(B5, B6) = 1152
- Grand Valley(A1) = 1150
- Grand Valley(IB5) = 1151
- Grand Valley Reverse = 1159
- Midfield Raceway = 1116
- Midfield Raceway(A3) = 1117
- Midfield Raceway(A6) = 1113
- Midfield Raceway(A8) = 1112
- Midfield Raceway(S4) = 1116
- Midfield Raceway Reverse = 1084
- Monaco = 330
- Monaco(SS8) = 330
- Laguna Seca = 651
- Laguna Seca(S6) = 651
- Laguna Seca(A2) = 623
- Laguna Seca(IA5) = 622
- Rome = 1259
- Rome(IA6) = 1212
- Rome Reverse = 1256
- Seattle = 2391
- Seattle(A7) = 2326
- Seattle(IB3) = 2346
- Seattle(IB4) = 2293
- Seattle(S2) = 2390
- Seattle Reverse = 2390
- Smokey Mountain = 656
- Smokey Mountain(R2) = 656
- Smokey Mountain Reverse = 643
- Special Stage Route 5 = 757
- Special Stage Route 5 Reverse = 758
- Super Special Stage Route 5 = 757
- Super Special Stage Route 5(S5) = 757
- Super Special Stage Route 5 Reverse = 758
- Special Stage Route 11 = 1162
- Special Stage Route 11(S7) = 1162
- Special Stage Route 11 Reverse = 1165
- Super Speedway = 687
- Swiss Alps = 869
- Swiss Alps(R3,R5) = 862
- Swiss Alps Reverse = 867
- Test Course = 241
- Test Course(Max speed test,400m,1000m) = 241
- Test Course(B1,B2 Tests) = 235
- Tokyo Route 246 = 1125
- Tokyo Route 246(IA1,IA4) = 1130
- Tokyo Route 246 Reverse = 1123
- Thaiti = 621
- Thaiti(R1,R4) = 647
- Thaiti Reverse = 621
- Thaiti Maze = 872
- Thaiti Maze(R8) = 872
- Thaiti Maze(R6,R7) = 896
- Thaiti Maze Reverse = 872
- Trial Mountain = 562
- Trial Mountain(S3) = 562
- Trial Mountain(B8 Test) = 538
- Trial Mountain(IA2 Test) = 551
- Trial Mountain Reverse = 531



