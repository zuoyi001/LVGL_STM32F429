# LVGL 在STM32F429 Discovery板的移植.

[STM32F429 Discovery kit](https://www.st.com/en/evaluation-tools/32f429idiscovery.html):
* 240x320 (QVGA) TFT
* Resistive touchscreen
* 180 MHz MCU
* 256KB RAM
* 64-MBit SDRAM
* GPU.

在 `hal_stm_lvgl/tft/tft.h` 中，可以enable/disable外部帧缓冲区和GPU

工程是用CubeIDE创建.


