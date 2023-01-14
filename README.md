# Picoprobe
  Picoprobe allows a Seeed Studio XIAO RP2040 to be used as USB -> SWD and UART bridge. This means it can be used as a debugger and serial console for another Pico.
  Ported from https://github.com/raspberrypi/picoprobe.

# Documentation
Picoprobe documentation can be found in the [Pico Getting Started Guide](https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf). See "Appendix A: Using Picoprobe".

XIAO RP2040 (D6) GP0/UART0 TX -> Pico GP1/UART0 RX
XIAO RP2040 (D7) GP1/UART0 RX -> Pico GP0/UART0 TX
XIAO RP2040 GND -> Pico GND
XIAO RP2040 (D8) GP2 -> Pico SWCLK
XIAO RP2040 (D10) GP3 -> Pico SWDIO
