# MPU9250-SPI-quaternionFilters

I am very bad with github so if someone wants to correct the structure of the repo i would be very glad

this is a mixed library born from the almost perfect Brian's library: https://github.com/brianc118/MPU9250
and the wonderful math magic of the quaternion filters: https://github.com/kriswiner/MPU9250
I made small mods to both libraries and now them works very well

you have to put "IMU_MPU9250" and "IMU_quaternionFilters" in your library folder and than you could use the sketch "MPU9250_quaternion_spi"
it is wrote for the stm32f103 but since it uses the arduino API will work in every board.

all the information are here: https://www.hackster.io/vincenzo-g/mpu9250-quaternion-filter-with-spi-011c81
