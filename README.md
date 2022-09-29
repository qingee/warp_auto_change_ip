warp_auto_change_ip
描述
这是warp的脚本。

您可以使用它来更改被 Netflix 阻止的 warp 的 IP。

更重要的是
大部分代码来自lmc999的流媒体检测脚本，非常感谢！

目前可以锁定区域（比如新加坡IP被锁定，IP分配给日本IP后会再次更改，直到IP为新加坡人）。

修改完成后会继续监控（每隔10s，可以自行修改），也可以放到屏幕后台执行。

如果需要一次性使用，将sleep 10改为break。

你最好使用193的IPv4范围，这样可以更好的解锁流媒体，如果他不清楚，请使用我的脚本安装warp。

如何使用

## How to use
```bash
wget https://github.com/qingee/warp_auto_change_ip/raw/main/warp_change_ip.sh && chmod +x warp_change_ip.sh && ./warp_change_ip.sh
```

PS：Will use the result of directly executing curl to Netflix as a benchmark.
