---
title: IOControlCode
second_title: Aspose.Slides for C++ API 參考文件
description: 列舉 IO 控制碼。
type: docs
weight: 157
url: /zh-hant/system.net.sockets/iocontrolcode/
---
## IOControlCode 列舉

列舉 [IO](../../system.io/) 控制碼。

```cpp
enum class IOControlCode : int64_t
```

### 成員

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| AsyncIO | -2147195267 | 啟用或停用 socket 的非同步 I/O 模式。 |
| NonBlockingIO | -2147195266 | 將 socket 標記為非阻塞。 |
| DataToRead | 1074030207 | 回傳可供讀取的位元組數。 |
| OobDataRead | 1074033415 | 回傳等待接收的帶外資料資訊。 |
| AssociateHandle | -2013265919 | 將此 socket 與伴隨介面的指定處理序關聯。 |
| EnableCircularQueuing | 671088642 | 當傳入訊息佇列已滿時，以新進來的資料報文取代最舊的佇列資料報文。 |
| Flush | 671088644 | 丟棄與此 socket 相關的傳送佇列中目前的內容。 |
| GetBroadcastAddress | 1207959557 | 回傳一個 SOCKADDR 結構，其中包含目前 socket 所屬位址族的廣播位址。 |
| GetExtensionFunctionPointer | -939524090 | 取得指向相關服務提供者所支援之指定擴充功能的指標。 |
| GetQos | -939524089 | 取得與 socket 相關的 QOS 結構。 |
| GetGroupQos | -939524088 | 回傳 socket 群組的 QOS 屬性。 |
| MultipointLoopback | -2013265911 | 控制本機電腦上應用程式於多播會話中所傳送的資料（不一定由相同 socket）是否會被加入至多播目的地群組且位於迴路介面的 socket 接收。 |
| MulticastScope | -2013265910 | 控制路由器轉發多播封包的次數，又稱為 TTL（存活時間）或跳數。 |
| SetQos | -2013265909 | 設定 socket 的 QOS 屬性。 |
| SetGroupQos | -2013265908 | 設定 socket 群組的 QOS 屬性。 |
| TranslateHandle | -939524083 | 回傳在伴隨介面情境下對 socket 有效的處理序。 |
| RoutingInterfaceQuery | -939524076 | 回傳可用於連線至指定遠端位址的介面位址。 |
| RoutingInterfaceChange | -2013265899 | 啟用在用於存取遠端端點的本機介面變更時接收通知。 |
| AddressListQuery | 1207959574 | 回傳 socket 可綁定的本機介面清單。 |
| AddressListChange | 671088663 | 啟用在 socket 協定族的本機介面清單變更時接收通知。 |
| QueryTargetPnpHandle | 1207959576 | 取得底層提供者的 SOCKET 處理序。 |
| NamespaceChange | -2013265895 | 控制 socket 在命名空間查詢變為無效時是否接收通知。 |
| AddressListSort | -939524071 | 排序 IPv6 與 IPv4 目的位址清單，以決定建立連線時的最佳可用位址。 |
| ReceiveAll | -1744830463 | 啟用接收網路上所有 IPv4 封包。 |
| ReceiveAllMulticast | -1744830462 | 啟用接收網路上所有多播 IPv4 封包。 |
| ReceiveAllIgmpMulticast | -1744830461 | 啟用接收網路上所有 IGMP 封包。 |
| KeepAliveValues | -1744830460 | 控制傳送 TCP keep-alive 封包以及其傳送間隔。 |
| AbsorbRouterAlert | -1744830459 | 此值等同於 Winsock 2 的 'SIO_ABSORB_RTRALERT' 常數。 |
| UnicastInterface | -1744830458 | 設定用於傳送單向封包的介面。 |
| LimitBroadcasts | -1744830457 | 此值等同於 Winsock 2 的 'SIO_LIMIT_BROADCASTS' 常數。 |
| BindToInterface | -1744830456 | 將 socket 綁定至指定的介面索引。 |
| MulticastInterface | -1744830455 | 設定用於傳送多播封包的介面。 |
| AddMulticastGroupOnInterface | -1744830454 | 使用以索引識別的介面加入多播群組。 |
| DeleteMulticastGroupFromInterface | -1744830453 | 將 socket 從多播群組中移除。 |

## 另請參閱

* 命名空間 [System::Net::Sockets](../)
* 函式庫 [Aspose.Slides](../../)