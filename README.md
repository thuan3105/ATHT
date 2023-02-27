sudo apt-key del ED444FF07D8D0BF6
sudo apt-key adv --keyserver hkp://keys.gnupg.net --recv-keys 7D8D0BF6
sudo apt-get clean all
sudo rm -rf /var/lib/apt/lists/*
sudo apt-get update
