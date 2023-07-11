# Tunneling wireguard

Encapsulating wireguard traffic into various tunnels.

Q: Wireguard might protect your data, but does it protect user? 

## Installation

Install rtptun, udp2raw and ctunnel into wireguard server and client(s).

This is tested to work with systemd-networkd wireguard configurations. 

## Usage

Start all services at wireguard server side. On client you can start
tunnel you like and it automatically shuts down previous one.

## Tunnels

[1] https://github.com/me-asri/rtptun.git

[2] https://github.com/wangyu-/udp2raw

[3] https://github.com/alienrobotarmy/ctunnel.git


