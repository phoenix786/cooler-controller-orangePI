## Cooler controller for OrangePI
This script measures temperature of cpu and turns on/off cooler if necessary.
Should work with any OrangePI.

[WiringOP](https://github.com/zhaolei/WiringOP.git) was used to measure temperature of Orange pi.


### Installation process
Enter password if needed

```bash
git clone https://github.com/phoenix786/cooler-controller-orangePI
cd cooler-controller-orangePI
sudo sh install.sh
```

### Components
* [Cooler](http://ali.pub/4f1j47)
* Transistor npn
* Some wires
* [Prototype PCB](http://ali.pub/4f1npv)

### Wiring
|               |                           |
| ------------- |:-------------------------:|
| Fan 5V        | OrangePI 5V               |
| Fan GND       | Transistor Collector (C)  |
| GPIO 7        | Transistor Base (B)       | 
| GND           | Transistor Emitter (E)    |

![schematic](https://github.com/Sabbaken/cooler-controller-orangePI/blob/master/img/schematica.png?raw=true)


![pinout](https://github.com/Sabbaken/cooler-controller-orangePI/blob/master/img/1033818249.jpg?raw=true)


![pinout_table](https://github.com/Sabbaken/cooler-controller-orangePI/blob/master/img/gpio.jpg?raw=true)

