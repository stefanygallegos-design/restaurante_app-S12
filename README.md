# Restaurante App - Semana 12

## Descripción

`restaurante_app` es una aplicación desarrollada en Python que permite gestionar información relacionada con usuarios, productos, ventas y stock de un restaurante.

En esta Semana 12 se mantiene la estructura modular desarrollada anteriormente y se incorporan mejoras en el uso de colecciones de Python para optimizar las búsquedas, consultas y validaciones frecuentes.

El objetivo principal es mejorar el rendimiento de las operaciones sin eliminar las colecciones principales utilizadas por el sistema.

---

## Objetivo

Optimizar las operaciones de búsqueda y consulta de información mediante el uso adecuado de colecciones como:

- `list`
- `dict`
- `set`

Se utilizan estructuras auxiliares para acceder de manera más rápida a información que posee claves únicas, como el código de un producto o la identificación de un usuario.

---

## Estructura del proyecto

```text
restaurante_app/
│
├── datos/
│   ├── productos.json
│   ├── usuarios.json
│   └── ventas.json
│
├── modelos/
│   ├── __init__.py
│   ├── producto.py
│   ├── usuario.py
│   └── venta.py
│
├── servicios/
│   ├── __init__.py
│   ├── archivo_servicio.py
│   └── restaurante.py
│
├── main.py
└── README.md
