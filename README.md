To use:

Grab a copy of the STM32Cube code from here: http://www.st.com/en/embedded-software/stm32cubef4.html

Unpack the codebase, then clone this repository in the GPIO example directory for the STM32F411RE board:

```
$ cd STM32Cube_FW_F4_V1.16.0/Projects/STM32F411E-Discovery/Examples/GPIO/GPIO_EXTI
$ git clone https://github.com/studiofuga/stm32cubef4-gpio-exti.git gcc
$ cd gcc
$ make
```

To flash the board you can use openocd:

```
$ openocd -f /usr/share/openocd/scripts/board/stm32f4discovery.cfg  -c "program build/flash.elf verify reset"
```



