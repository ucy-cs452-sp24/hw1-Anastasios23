[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Sru7PNtP)

# Homework Assignment 1

This graph presents a comparison of different performance metrics across four categories:
Local DRAM, Local Disk, Rack DRAM, and Rack Disk.
The metrics evaluated are Latency, Bandwidth, and Capacity.

# Capacity(GB)

The are 2 identical nodes. They have the same capacities for the DRAM and Local Disk at 125GB and 466GB.

# Latency (us)

The DRAM has the lowest latency with just 110ns.
The latency to reach the remote DRAM is lower at 150us compare to the disk with 309us.
I added network latency with Local disk's to get the remote disk latency.

# Bandwidth(MB/s)

The highest speed is on the local DRAM with 48062MB/s.
The Local Disk's bandwidth is 191 MB/s, which is modest in comparison but consistent with typical disk speeds.
The remote DRAM bandwidth is the bottleneck of the network with 653.75MB/s.
The same with remote Disk bandwith is the bottleneck between local disk bandwidth and network bandwith so
it's the same with local disk bandwith 191 MB/s.

## Conclusion

We understand that is better to reach remote DRAMS because we have higher bandwidth
because network is the bottleneck.
