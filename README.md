# gitsync
Synchronize and manage web pages stored in a git repository.

## Usage
Under composition...

## Installation
- You can either [download](https://github.com/tamas646/gitsync/raw/main/gitsync_2.3.4_all.deb) and install the deb package or use the source code and setup it yourself.

- If you wish, you can install it from my apt repository too:

  ```sh
  sudo echo "deb [signed-by=/usr/share/keyrings/ptamas-pub.gpg] http://apt.ptamas.hu/main/ ./" > /etc/apt/sources.list.d/apt.ptamas.list
  wget -qO - https://apt.ptamas.hu/ptamas-pub.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/ptamas-pub.gpg > /dev/null
  apt update && apt install gitsync
  ```

