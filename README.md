# AvatarSim

This repository contains an avatar environment that can be programaticly controlled from Python via AirSim (https://github.com/Microsoft/AirSim).

## Executable:

The executable (avatarsim.exe) includes the avatar envrionment.  It is compiles for Windows 10 and runs best Nvidia GTX 1080i GPU or higher.  An AirSim settings file is also included that 

## Avatar Control Scripts:

Python scripts are included in the repository that illustrate how to control the avatar's facial pose and expressions in order to generate face images for testing face detection algorithms. Parameters that can be controlled programmaticly are: skin tone, age, head pose, head position, facial actions based on the Facial Action Coding System (FACS). 

```python
import airsim

client = airsim.VehicleClient()
client.confirmConnection()
```

Head Pose and Position:


Skin Tone and Age:


Facial Coding:




## Commerical Face API Scripts:

We include example python scripts for a set of commercial face detection APIs. These scripts show how to interrogate the APIs with images generated from the avatar environment. 
