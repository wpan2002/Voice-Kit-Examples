# Voice-Kit-Examples
Setup Instructions:
1. Pair AIY Voice box with AIY app
2. Get ip address from app 
3. use ssh to pair with pi@[ip address]
4. You are now connected to the AIY voice box

Google Assistant demo Instructions:
1. Navigate to ~/AIY-projects-python/src/examples
2. run voice/assistant_grpc_demo.py

Youtube-Dl Instructions
1. Install youtube-dl with sudo -H pip install youtube-dl
2. Run youtube-dl -F [link to video]
3. Find option you want and run youtube-dl -f [number of option] [link to video]
4. Get player with sudo apt-get install vlc
4. PLay video by running vlc [downloaded video]
