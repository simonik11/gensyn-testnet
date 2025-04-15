Install other dependencies
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof nano unzip
Install Node.js and npm
curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash
Create a screen session
screen -S gensyn
Run the swarm
cd $HOME && rm -rf gensyn-testnet && git clone https://github.com/zunxbt/gensyn-testnet.git && chmod +x gensyn-testnet/gensyn.sh && ./gensyn-testnet/gensyn.s
