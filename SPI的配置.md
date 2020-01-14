# SPI的配置

SPI，我配置了三天，最后终于成功了。

这几天我的一些参考链接都在这里：

https://devtalk.nvidia.com/default/topic/1061668/jetson-agx-xavier/spi1-on-xavier/
https://devtalk.nvidia.com/default/topic/1061177/jetson-agx-xavier/flashing-xavier-with-modified-device-tree/post/5375515/#5375515)
https://devtalk.nvidia.com/default/topic/1061457/
https://devtalk.nvidia.com/default/topic/1049488
https://devtalk.nvidia.com/default/topic/1050427
https://elinux.org/Jetson/TX2_SPI#Locating_the_SPI_Pins
https://docs.nvidia.com/jetson/archives/l4t-archived/l4t-322/index.html#page/Tegra%2520Linux%2520Driver%2520Package%2520Development%2520Guide%2Fkernel_custom.html%23wwpID0E0ZC0HA
https://docs.nvidia.com/jetson/l4t/index.html#page/Tegra%2520Linux%2520Driver%2520Package%2520Development%2520Guide%2Fflashing.html%23wwpID0E0ID0HA
https://devtalk.nvidia.com/default/topic/1044595/jetson-agx-xavier/question-how-do-i-enable-and-address-spi-ports-/1
https://devtalk.nvidia.com/default/topic/1042964/jetson-agx-xavier/the-spi-device-can-not-be-used/post/5293576/#5293576

如果你看了上面的一些链接，你会对Jetson有一些了解，虽然不是很多。如果你不想去看，那就直接开始配置SPI了。

## 刷机

如果你已经刷机了，那就跳过这一步