# Red Básica de Oficina – Cisco Packet Tracer

Simulación de una red básica de oficina diseñada en **Cisco Packet Tracer**, compuesta por **1 router, 1 switch y 6 PCs**. El laboratorio está orientado a comprender los fundamentos del direccionamiento IP, la conmutación y el enrutamiento básico en una red local.

---

## 📌 Descripción del proyecto

Este proyecto representa una red típica de una pequeña oficina donde varios equipos finales se comunican a través de un switch y utilizan un router como **gateway** para la comunicación entre redes (y potencial acceso a Internet). Se aplican conceptos básicos de redes siguiendo buenas prácticas.

---

## 🎯 Objetivos

* Implementar una red LAN básica de oficina
* Configurar correctamente un router y un switch
* Asignar direccionamiento IP estático a los dispositivos
* Verificar la conectividad entre los equipos finales
* Comprender el rol del router como puerta de enlace

---

## 🖧 Topología de red

La topología está compuesta por:

* 1 Router
* 1 Switch (capa 2)
* 6 PCs

  [](/topologia.png)


---

## 🛠️ Tecnologías y herramientas utilizadas

* Cisco Packet Tracer 8.x
* IPv4
* Direccionamiento IP estático
* Switch capa 2
* Router como gateway

---

## 🌐 Direccionamiento IP

| Dispositivo | Interfaz | Dirección IP | Máscara       | Gateway     |
| ----------- | -------- | ------------ | ------------- | ----------- |
| Router      | G0/0     | 192.168.0.1  | 255.255.255.0 | —           |
| PC1         | NIC      | 192.168.0.10 | 255.255.255.0 | 192.168.0.1 |
| PC2         | NIC      | 192.168.0.11 | 255.255.255.0 | 192.168.0.1 |
| PC3         | NIC      | 192.168.0.12 | 255.255.255.0 | 192.168.0.1 |
| PC4         | NIC      | 192.168.0.13 | 255.255.255.0 | 192.168.0.1 |
| PC5         | NIC      | 192.168.0.14 | 255.255.255.0 | 192.168.0.1 |
| PC6         | NIC      | 192.168.0.15 | 255.255.255.0 | 192.168.0.1 |

## ▶️ Cómo abrir el proyecto

1. Instalar **Cisco Packet Tracer** (versión 8.2 o superior)
2. Descargar el archivo `.pkt` del repositorio
3. Abrir el archivo con Cisco Packet Tracer

---

