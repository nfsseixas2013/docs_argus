# Instalação do proxmox em baremetal (Direto na máquina)

Criar um pendrive bootável do arquivo. Sugestão: Uso do balena ou ventoy

Link para downlaod do Balena etcher: https://github.com/balena-io/etcher/releases?page=1

Ex. Uso do Balena

![Screenshot from 2024-04-29 08-34-59.png](Instalac%CC%A7a%CC%83o%20do%20proxmox%20em%20baremetal%20(Direto%20na%20ma%20247ace9e0c0e4cf996e3bb6df65e5f46/Screenshot_from_2024-04-29_08-34-59.png)

## Baixar o proxmox da página proxmox.com/en/downloads

![Screenshot from 2024-04-29 08-33-49.png](Instalac%CC%A7a%CC%83o%20do%20proxmox%20em%20baremetal%20(Direto%20na%20ma%20247ace9e0c0e4cf996e3bb6df65e5f46/Screenshot_from_2024-04-29_08-33-49.png)

### Escolha do HD do proxmox

![Screenshot from 2024-04-29 08-43-46.png](Instalac%CC%A7a%CC%83o%20do%20proxmox%20em%20baremetal%20(Direto%20na%20ma%20247ace9e0c0e4cf996e3bb6df65e5f46/Screenshot_from_2024-04-29_08-43-46.png)

# Importante. Configurar o raid para redundância/tolerância a falhas de dados

## Defina país, time zone e layout de keyboard como na imagem

![Screenshot from 2024-04-29 08-44-14.png](Instalac%CC%A7a%CC%83o%20do%20proxmox%20em%20baremetal%20(Direto%20na%20ma%20247ace9e0c0e4cf996e3bb6df65e5f46/Screenshot_from_2024-04-29_08-44-14.png)

## Definição de IP

ip: 200.128.51.155
máscara: 255.255.255.0 ou /24
gateway: 200.125.51.1
dns: 8.8.8.8
hostname: argus.proxmox

![Screenshot from 2024-04-29 08-45-05.png](Instalac%CC%A7a%CC%83o%20do%20proxmox%20em%20baremetal%20(Direto%20na%20ma%20247ace9e0c0e4cf996e3bb6df65e5f46/Screenshot_from_2024-04-29_08-45-05.png)

## Acesso após a instalação:
200.128.51.155:8006