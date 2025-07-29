# STM32 Stepper Positioner 🎯

Proyecto bare-metal en C usando un STM32F103C8T6 (Blue Pill), un motor paso a paso 28BYJ-48 con ULN2003 y un potenciómetro.

📌 **Objetivo**: controlar la posición del motor proporcionalmente a la lectura del potenciómetro.

## 🛠 Hardware
- STM32F103C8T6
- Motor paso a paso 28BYJ-48
- ULN2003AN (driver)
- Potenciómetro 10kΩ
- Fuente de 5V

## ⚙️ Funcionalidad
- El usuario gira el potenciómetro
- El motor se posiciona proporcionalmente
- Controlado por software bare-metal en C

## 🚀 Extensiones planeadas
- Mostrar posición con ESP32 como pantalla serial remota
- Agregar control por botones
- Ajuste de velocidad desde otro potenciómetro
- Visualización por UART

## 📸 Imágenes / video (pendiente)
