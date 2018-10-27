This README serves as a quick start docuement. For more detailed documentation, please visit website: http://seawolf.io

seawolf.io.service helps user of linux devices to get dynamic IP after power up without the needs of monitor, keyboard and mouse. I use it for all my raspberry pi boxes.

Once the device is powered up, go to http://seawolf.io to get the private IP.

The site saves the data for maxium 6 minutes. It can be accessed only from the same IP where the data is posted from. The access links:

  http://seawolf.io       for human to read
  http://seawolf.io/api   for program to access
  http://seawolf.io/once  delete after being read

Install seawolf.io.service
--------------------------

curl https://raw.githubusercontent.com/seawolf.io/seawolf.io/master/download/install | sh
