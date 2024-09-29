# TCP Flood Attack Script in Go

This Go-based script is designed to perform TCP flood attacks by generating a large volume of TCP packets towards a specified target. It utilizes random source IP addresses and supports multiple threads to maximize the attack's effectiveness.

## Features

- **Randomized Source IPs**: Each packet is sent from a randomly generated source IP address to evade detection.
- **Configurable Parameters**: Users can specify the target IP, destination port, number of threads, packets per second (PPS), and the duration of the attack.
- **Multi-threading Support**: The script can run multiple threads simultaneously, increasing the overall packet output and enhancing the attack's impact.
- **Checksum Calculation**: TCP/IP checksum is calculated for each packet to ensure data integrity.

## Usage

To run the script, use the following command format:

```bash
go run main.go <target IP> <port> <num threads> <pps> <time>
