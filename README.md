### ESP32 Project example based on a1waras/esp32 docker image

#### How to run
For docker preparations [take a look into image repo](https://github.com/spaivaras/docker/tree/master/esp32)

```
$ docker-compose run dev
$ cd src
$ make menuconfig
$ make all
$ make flash monitor
```
__NOTE__ Even if you don't need any settings changed in esp-edf environment you need to run make menuconfig atleast once

#### Legal
Code in this repository is Copyright (C) 2016 Espressif Systems, licensed under the Apache License 2.0 as described in the file LICENSE.

[Espressif IoT Development Framework](https://github.com/espressif/esp-idf)

