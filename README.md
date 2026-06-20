# Sumador/Restador de 4 bits con detección de Overflow

**Descripción:** Este circuito lógico combinacional es capaz de sumar o restar dos valores de 4 bits (A y B) basándose en una señal de control (M), utilizando el método de complemento a 2 para la resta. Además, incorpora lógica para detectar cuándo el resultado supera el rango representable (Overflow).

**Entradas:**
* A (4 bits) - DIP Switch Azul Izquierdo
* B (4 bits) - DIP Switch Azul Derecho
* M (Selector de modo: 0=Suma, 1=Resta) - Interruptor deslizante.

**Salidas:**
* S (Suma/Resta) - 4 LEDs Rojos.
* Overflow (Acarreo/Desbordamiento) - 1 LED Azul.
