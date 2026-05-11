# Proyecto de Infraestructura de Red - SDG, S.A.

Diseño e implementación de una red empresarial escalable para la consultora **Soluciones Administrativas Globales (SDG, S.A.)**.

> **Nota:** El proyecto completo, incluyendo todos los entregables y documentación técnica, se encuentra consolidado en un solo documento dentro de este repositorio.

##  Tecnologías y Herramientas
* **Simulación:** Cisco Packet Tracer.
* **Hardware:** Router Cisco 2911, Switch Multicapa 3560, Switch 2960.
* **Protocolos:** NAT/PAT, Inter-VLAN Routing, DHCP, DNS.

##  Estructura de la Red
La red está segmentada en VLANs para optimizar la seguridad y el rendimiento:
* **VLAN 10 (Admin):** Gestión y servidores.
* **VLAN 20 (Staff):** Puestos de trabajo operativos.
* **VLAN 30 (Guest):** Acceso para invitados.

##  Configuración Clave
- **Enrutamiento:** SVI en el switch core y rutas estáticas.
- **Seguridad:** Aislamiento de tráfico mediante VLANs y NAT/PAT para salida segura a Internet.
- **Automatización:** Servidor DHCP centralizado para asignación dinámica de direcciones.

##  Requisitos
Para visualizar o editar los archivos de configuración, se recomienda utilizar **Cisco Packet Tracer**.

---
*Proyecto por Nicky Cetro Fernandez.*
 
