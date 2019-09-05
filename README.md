# Info
=======
Fork https://github.com/lanceshelton/irqstat

irqstat


A better way to watch /proc/interrupts, designed for NUMA systems with many processors.

# Install
=======
yum -y install numactl
wget https://github.com/zops/irqstat/archive/v1.0.0.tar.gz
tar xf v1.0.0.tar.gz
mv irqstat /usr/local/bin/

# Use example
=======
irqstat 
irqstat -t 2 -n 0
