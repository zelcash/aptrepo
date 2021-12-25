# Zel Technologies APT repository

Use the following to set it up. 
```
echo 'deb https://apt.zel.network/ all main' | sudo tee --append /etc/apt/sources.list.d/zelcash.list
gpg --keyserver keyserver.ubuntu.com --recv 4B69CA27A986265D
gpg --export 4B69CA27A986265D | sudo apt-key add -

sudo apt-get update
sudo apt-get install zelcash # to install ZelCash
sudo apt-get install zelcashswingwallet # to install ZelCash Swing Wallet
sudo apt-get install zelcore # to install ZelCore
sudo apt-get install zelbench # to install ZelBench
```

## Available Packages
```
## AMD64
zelcash
        Depends: libc6 (>= 2.17), libgcc1 (>= 1:3.0), libgomp1 (>= 4.9), libstdc++6 (>= 5.2)

zelcashswingwallet
        Depends: default-jdk, zelcash

zelcore
        Depends: 

zelbench
        Depends: libc6 (>= 2.17), libgcc1 (>= 1:3.0), libgomp1 (>= 4.9), libstdc++6 (>= 5.2)
```
