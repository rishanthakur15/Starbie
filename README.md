# Starbie
A tiny gesture/motion-controlled digital pet, basically a desktop Tamagotchi. 
So Starbie is a pocket-sized, AI-powered digital pet built around the Seeed Studio XIAO ESP32-S3 Sense .
Features:
​Offline Edge AI: Powered by a customized, quantized MobileNetV2 model trained via Edge Impulse. All object and gesture recognition processing runs entirely offline on the ESP32-S3 chip for immediate reaction times and strict data privacy.
​Gesture-Triggered Reactions: The onboard OV3660 camera continuously feeds live visual data to the AI model. Specific gestures trigger unique state changes and animations (e.g., feeding, sleeping, happiness).
​Integrated Charging: Features built-in battery management. The connected 3.7V Micro LiPo battery safely recharges automatically whenever the device is plugged in via USB-C.
