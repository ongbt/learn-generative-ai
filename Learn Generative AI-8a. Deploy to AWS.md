
1. Create Instance
   1. Ubuntu 22
2. Update
   1. sudo apt update
   2. sudo apt-get update
   3. sudo apy upgrade -y
3. Install dependencies
   1. sudo apt install git curl unzip tar make sudo vim wget python3-pip -y
4. Clone repo
   1. git clone <repo>
5. Setup
   1. pip3 install -r requirement.txt
   2. touch .env
      1. vi .env 
      2. Add OPENAI_API_KEY
6. Run Streamlit
   1. python3 -m streamlit StreamlitAPP.py
7. Configure AWS security group
   1. Add inbound rule for 8051, from 0.0.0.0/0