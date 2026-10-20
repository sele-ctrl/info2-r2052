# 🥤 Demo ESP32 Bridge UART TCP

## Proyectos

### 1. VS Code para ESP32
    Server_Bridge_UART.zip (chequear versión del kit del ESP32 para que coincidad los pines de la UART)
### 2. QT app
    NodeMcuTCPClient.zip
### 3. LPC845 app
    MQTT_Client.zip
            

## Requisitos

### 1. Plugin ESP-IDF
![Plugins.png](./images/Plugins_2025-09-03-07-15-13.png) 

### 2. Variables de entorno
Exportar variables de entorno para poder utilizar los botones que vienen con VS code al instalar el plugin ESP-IDF

Ejemplo:
export IDF_PATH='/home/marianito/esp/esp-idf'
![Env.png](./images/Env_2025-09-03-07-16-02.png)

### 3. Botones build, flash y monitor VS Code

![Buttons.png](./images/Buttons_2025-09-03-07-17-02.png)

### 4. Compilación

![Build.png](./images/Build_2025-09-03-07-16-38.png)

### 5. Grabar ESP-32

![Flash.png](./images/Flashing_2025-09-03-08-23-22.png)

### 6. Monitorear APP

![Monitor.png](./images/Monitoring_2025-09-03-08-25-25.png)

### 7. Chequear misma LAN PC y ESP-32

![LAN_PC.png](./images/WiFi_SSID_SO_2025-09-03-08-26-57.png)

![LAN_ESP32.png](./images/LAN_ESP32_2025-09-03-08-27-21.png)

### 8. Prueba cliente TCP via terminal

![Test_TCP_Client.png](./images/Telnet_2025-09-03-08-27-21.png)