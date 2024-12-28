# SSD1306_DotMatrixDisplay_SPI
 
Tested on NUCLEO-F767ZI board (code imported to STM32CubeIDE).

https://github.com/afiskon/stm32-ssd1306

https://www.aliexpress.com/item/1005006100836064.html 
selected 7pin SPI version, refresh rate 33Hz according to SPI speed set at 375 KBits/s

// Choose a bus (ssd1306_config.h)
#define SSD1306_USE_I2C
//#define SSD1306_USE_SPI

I2C version 9Hz refresh rate, more stable
VSS 3.3V (CN11-16) VDD Gnd (CN11-71), SCL=PB8(CN12-3), SDA=PB9(CN12-5)

SPI Version
VSS 	3.3V 	(CN11-16)
VDD	 Gnd	(CN11-71)
SCLK	CLK	PA5 (CN12-11)
SDA 	MOSI	PB5 (CN12-29)
RES		PB1 (CN12-24)
DC		PC2  (CN11-35)
CS		PC0 (CN11-38)


![20241213_184540](https://github.com/user-attachments/assets/e9d08c6f-cfdd-437c-aa60-f398f6b49ed9)
