## Project Name
    Xcom - Mimic (for now)
## Description
    To create a turn-based tactical game that is similar to Xcom 1 or Xcom 2.
## Author
    @Hugo Ng
## Stage
    Prototyping
## Language
    C++
## Environment
    Visual Studio 2022 (Windows)
    Visual Studio Code (MacOS)
    aviary.cs.umanitoba.ca (Linux)
## How to play
    execute Driver

## Structure
    0. Driver

    1. Setting
    
    2. Character (abstract)
        2.1 Controllable (abstract)
            2.1.1 Soldier
                2.1.1.1 Ranger
                2.1.1.2 Grenadier
                2.1.1.3 SharpShooter
                2.1.1.4 Specialist
        2.2 Enemy (abstract)

    3. Item (abstract)
        3.1 FireArm (abstract)
            3.1.1 Rifle
            3.1.2 Pistol 
            3.1.3 SniperRifle 
            3.1.4 MachineGun 
            3.1.5 ShotGun 
        3.2 Throwable (abstract)
            3.2.1 FragGrenade 
            3.2.2 SmokeGrenade 
            3.2.3 FlashGrenade 

    4. Field
        4.1 GameBoard 
