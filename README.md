# 🛡️ Laboratorio SOC (Purple Team): Monitorización y Respuesta

**Proyecto Final del Ciclo Superior de ASIR** enfocado en ciberseguridad defensiva (Blue Team) y simulación de amenazas (Red Team).

## 📝 Descripción
Este proyecto demuestra el despliegue y configuración de una infraestructura de red segura y monitorizada. El objetivo es detectar, alertar y analizar ataques dirigidos contra un servidor web expuesto, utilizando herramientas estándar de la industria.

## 🏗️ Arquitectura y Tecnologías
*   **Firewall / Router:** pfSense
*   **IDS / IPS:** Suricata (integrado en pfSense para análisis de tráfico)
*   **SIEM / XDR:** Wazuh (para recolección de logs y detección en endpoints)
*   **Atacante:** Kali Linux
*   **Víctima:** Servidor Web (Apache/Nginx en Linux)

<img width="530" height="692" alt="image" src="https://github.com/user-attachments/assets/60aed163-6a2d-4989-8d46-6de089668fcd" />


## ⚔️ Casos de Uso: Ataque y Detección

### 1. [Nombre del Ataque 1, ej. Escaneo Agresivo Nmap / Dirb]
*   **Vector de ataque (Red Team):** Desde Kali Linux se ejecutó... *[explicar brevemente]*
*   **Detección (Blue Team):** Suricata detectó anomalías en el tráfico de red, generando una alerta de prioridad alta. A su vez, Wazuh registró...
*(Nota: Añadir un GIF o captura de la alerta de Wazuh/Suricata aquí)*

### 2. [Nombre del Ataque 2, ej. Fuerza Bruta SSH / SQL Injection]
*   **Vector de ataque:** ...
*   **Detección:** ...

## 📂 Documentación Adjunta
*   [`/docs/Memoria_Proyecto_ASIR.pdf`](#): Documento completo con la explicación paso a paso de la configuración.
*   **Vídeo demostrativo:** [Enlace a YouTube oculto con el funcionamiento en directo]
