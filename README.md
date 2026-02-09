https://github.com/xisohi/CHINA-IPTV?tab=readme-ov-file

一、可用 m3u 源（2026-02-09 测试有效）
上海电信公网转单播源（推荐）
plaintext
https://raw.githubusercontent.com/ihipop/Shanghai-IPTV/master/tel_mu.m3u8
特点：含东方卫视、五星体育等本地台，已通过 udpxy 转 HTTP，OpenWrt / 播放器直接播。
上海电信酒店源（稳定）
plaintext
http://180.165.26.94:6000/tsfile/live/tvlist.m3u8?key=txiptv&playlive=1&authid=0
特点：50 + 频道，含央视 / 卫视 / 本地台，HTTP 直连。
备用聚合源（防失效）
plaintext
https://itv.aptv.app/china-iptv/shdx.m3u
特点：自动更新，含上海电信专线源，适合长期用。
