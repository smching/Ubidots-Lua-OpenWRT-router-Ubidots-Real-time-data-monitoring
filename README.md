### Ubidots-Lua: OpenWRT router + Ubidots = Real time data monitoring
Ubidots is a cloud service to store and analyze sensor data in real-time.

Ubidots-Lua is written in Lua, it allows you to post data to or get data from Ubidots with minimum coding required. Ubidots-Lua should run on any OpenWRT wireless router, and it is able to execute from console, Bash script or as a Lua function call.

####Installing Ubidots-Lua
There is no need to run a specific installation program, just put the file to your wireless router (/usr/lib/lua directory), giving execution permission and run it.

####Execute ubidots-Lua from command-line interpreter

**This will post a value of 100 to your Ubidots Variable:**
* /usr/lib/lua/ubidots.lua -post api_key deviceID 100

**Retrieve last value from Ubidots Variable:**
* /usr/lib/lua/ubidots.lua -get api_key deviceID

**Retrieve all data from Ubidots Variable:**
* /usr/lib/lua/ubidots.lua -get api_key deviceID all

**Retrieve last value from Ubidots Variable and save it to router /tmp/data.txt directory:**
* /usr/lib/lua/ubidots.lua -get api_key deviceID last data.txt


You can read more about this project on my website. http://ediy.com.my/index.php/projects/item/121-ubidots-lua-openwrt-router-ubidots-real-time-data-monitoring

