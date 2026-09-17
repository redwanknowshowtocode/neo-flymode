# neo-flymode
<img width="628" height="403" alt="image" src="https://github.com/user-attachments/assets/ed322d78-5d81-4016-a6ff-ecf585fc8a3a" />

# Why I built this

I wanted to get started making drones so this is my first drone I wanted to just practice with. Since I didn't want to immediately go into FPV Drones I decided to settle with a regular drone with a camera for recording. 

# Features
 
- Powered by 4x EMAX ECO Micro 1404 Brushless Motors (6000KV)
- Flight controlled via SpeedyBee F405 V4 Stack (F405, 20x20mm, 4-in-1 ESC)
- Runs on a Gaoneng GNB 15.2V 4S 660mAh 90C LiHV battery (XT30 connector)
- 3" tri-blade propellers for balanced thrust and efficiency
- Onboard RunCam Split 4 V3 camera — records up to 4K@30fps / 1080p@60fps to microSD
- Custom-designed frame (CAD modeled)
- 3D-printed TPU camera mount (adapted from iFlight Chimera 4 holder)

# How It Works
 
1. **Power** — The 4S LiHV battery supplies power through the SpeedyBee F405 stack, which regulates voltage to the flight controller, ESCs, and onboard camera via its BEC pad.
2. **Flight Control** — The SpeedyBee F405 processes pilot input and sensor data (gyro/accelerometer) to calculate motor throttle signals.
3. **Thrust** — The 4-in-1 ESC on the stack drives each of the 4 EMAX 1404 6000KV motors independently, spinning the 3" propellers to generate lift and control pitch, roll, and yaw.
4. **Recording** — The RunCam Split 4 V3 camera, mounted via the 3D-printed TPU holder, records flight footage directly to a microSD card for later review.
5. **Frame** — The custom CAD-designed frame holds all components together, with the arm geometry positioning the motors for stable flight.

# Bill of Materials
 
| Component | Part | Qty | Price | Link |
|---|---|---|---|---|
| Frame | Custom Carbon Fiber Drone Frame | 1 | $38.99 | [5.0mm 200x300mm 100% Carbon Fiber Sheet](https://www.amazon.com/cncarbonfiber-200x300mm-Carbon-Laminate-Finish/dp/B07GCYG6L5/ref=sr_1_8?dib=eyJ2IjoiMSJ9.K9cS7RyeqTtBFRq5nBnWjUVrVW6M-62arL_GdbVi_T_5BzzV7CZZtNx4a3pMbiFifinGjUnDCVWEyiYUQaNgWDfVNpTieGp0kaeEsStYVnD4yasak2V4caMnYLLcfncTJUwt8kYV4_12wgj1bSDXQsPaHRp6QfuCO5q1rJseYb7Qu_8j5hUhtavILqH9mxqvfFcSebIu8dlsH6idwgMO5fNWQK-0P5aLUhxfg2_Aeo0.rPusb6zhIkrvfwaveUovr0-Gkwu5rvVp9Ufwy9E7vZ8&dib_tag=se&keywords=5mm%2Bcarbon%2Bfiber%2Bsheet&qid=1789655379&sr=8-8&th=1) |
| Motors | EMAX ECO Micro 1404 Brushless Motor (6000KV) | 4 | $51.96 | [EMAX ECO Micro 1404 Brushless Motor (6000Kv)](https://www.bhphotovideo.com/c/product/1818750-REG/emax_ecom14046000_brushless_motor_for_eco.html/?ap=y&ap=y&smp=y&smp=y&store=420&lsft=BI%3A514&gad_source=1&gad_campaignid=11184208315&gbraid=0AAAAAD7yMh1w-WKfu1IORi0vGotQaN9iN&gclid=Cj0KCQjwnbrUBhDOARIsAKKhPpd4A9SnQRXThEcxaw3a5Hlejx30iY9ClMeS0aExU7wIZxmF9HVmyYkaAr4LEALw_wcB) |
| Flight Controller / ESC | SpeedyBee F405 V4 Stack (20x20mm, 4-in-1 ESC) | 1 | $64.99 | [SpeedyBee F405 Mini BLS 35A 20x20 Stack](https://www.speedybee.com/speedybee-f405-mini-bls-35a-20x20-stack/) |
| Battery | Gaoneng GNB 15.2V 4S 660mAh 90C LiHV (Long Type, XT30) | 1 | $14.99 | [Tattu 550mAh 4S 95C 15.2V(HV) Long Lipo Battery](https://genstattu.com/tattu-550mah-4s-95c-15-2v-hv-lipo-battery-long-pack-with-xt30-plug/?srsltid=AfmBOoo0jFcU9BbyadZF8PSRTFwhqyYSVPKVMJ-JEhh96vA7yHntuIW8) |
| Propellers | 3" Tri-blade Prop (e.g. Gemfan Hurricane 3018) | 4 | $12.99 | [Gemfan Hurricane 3630 3.6X3.0X3 3-Blade Propeller](https://www.amazon.com/dp/B0DDYNQ282?lv=shuf&channelId=500&plpRedirect=mhFallback) |
| Camera | RunCam Split 4 V3 | 1 | $89.99 | [RunCam Shop](https://shop.runcam.com/runcam-split-4-v3/) |
| Camera Mount | iFlight Chimera 4 RunCam Split 4k holder (TPU, 3D printed) | 1 | Free (STL) | [Printables](https://www.printables.com/model/58485-iflight-chimera-4-runcam-split-4k-holder) |

Total: $273.82
