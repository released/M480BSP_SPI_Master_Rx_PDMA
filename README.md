# M480BSP_SPI_Master_Rx_PDMA
 M480BSP_SPI_Master_Rx_PDMA


update @ 2022/11/16

1. initial SPI1 w/ PDMA function

	PB4 : MOSI
	
	PB5 : MISO
	
	PB3 : CLK
	
	PB2 : SS

2. with 2 define ENALBE_PDMA_IRQ ,  ENALBE_PDMA_POLLING , for PDMA transfer function

3. execute write and read per 50 ms , packet length : 32

below is tx , with array[0] is counter , array[1] = 0x5A , array[31] = 0xA5 for indicator

![image](https://github.com/released/M480BSP_SPI_Master_Rx_PDMA/blob/main/TX.jpg)	

below is rx clock , 

![image](https://github.com/released/M480BSP_SPI_Master_Rx_PDMA/blob/main/RX.jpg)	

