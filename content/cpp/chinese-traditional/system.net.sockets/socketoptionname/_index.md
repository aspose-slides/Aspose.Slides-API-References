---
title: SocketOptionName
second_title: Aspose.Slides for C++ API 參考
description: 為 Socket 類別定義 socket 選項名稱。
type: docs
weight: 248
url: /zh-hant/system.net.sockets/socketoptionname/
---
## SocketOptionName 列舉

定義 [Socket](../socket/) 類別的 socket 選項名稱。

```cpp
enum class SocketOptionName
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Debug | 1 | 記錄除錯資訊。 |
| AcceptConnection | 2 | 表示 socket 是否在等待傳入連線。 |
| ReuseAddress | 4 | 表示 socket 是否可以綁定至已在使用的位址。 |
| KeepAlive | 8 | 啟用 socket 連線的「Keep-Alive」封包。 |
| DontRoute | 16 | 表示封包是否直接發送至介面位址。 |
| Broadcast | 32 | 表示 socket 是否能發送廣播訊息。 |
| UseLoopback | 64 | 盡可能繞過硬體。 |
| Linger | 128 | 系統將在關閉嘗試時阻塞程序，直到資料傳輸完成。 |
| OutOfBandInline | 256 | 在一般資料流中接收非同步資料。 |
| DontLinger | n/a | 表示 socket 將在不延遲關閉的情況下關閉。 |
| ExclusiveAddressUse | n/a | socket 將排他性地使用已綁定的位址。 |
| SendBuffer | 4097 | 指定傳送緩衝區大小。 |
| ReceiveBuffer | 4098 | 指定接收緩衝區大小。 |
| SendLowWater | 4099 | 指定傳送操作的最小資料量。 |
| ReceiveLowWater | 4100 | 指定接收操作的最小資料量。 |
| SendTimeout | 4101 | 指定同步傳送操作的逾時時間。 |
| ReceiveTimeout | 4102 | 指定同步接收操作的逾時時間。 |
| Error | 4103 | 回傳錯誤狀態並清除。 |
| Type | 4104 | 回傳 socket 類型。 |
| ReuseUnicastPort | 12295 | 表示系統是否應延遲為外向連線分配臨時埠號。 |
| MaxConnections | 2147483647 | 此選項不受支援。它曾用於指定監聽的最大佇列長度。 |
| IPOptions | 1 | 指定必須插入至外送資料報的 IP 選項。 |
| HeaderIncluded | 2 | 標頭已包含在外送資料報中。 |
| TypeOfService | 3 | 變更 IP 標頭服務欄位的類型。 |
| IpTimeToLive | 4 | IP 的生存時間 (TTL)。 |
| MulticastInterface | 9 | 設定外送多播封包的介面。 |
| MulticastTimeToLive | 10 | IP 多播的生存時間 (TTL)。 |
| MulticastLoopback | 11 | IP 多播回送。 |
| AddMembership | 12 | 新增 IP 群組成員資格。 |
| DropMembership | 13 | 刪除 IP 群組成員資格。 |
| DontFragment | 14 | 不要分割 IP 資料報。 |
| AddSourceMembership | 15 | 加入 IP 群組/來源。 |
| DropSourceMembership | 16 | 移除 IP 群組/來源。 |
| BlockSource | 17 | 封鎖 IP 群組/來源。 |
| UnblockSource | 18 | 解除封鎖 IP 群組/來源。 |
| PacketInformation | 19 | 接收 IPv4 的封包資訊。 |
| HopLimit | 21 | 傳遞包含封包跳數的整數。 |
| IPProtectionLevel | 23 | 啟用對 IPv6 socket 之指定範圍的限制。 |
| IPv6Only | 27 | 此 socket 僅限制傳送與接收 IPv6 封包。 |
| NoDelay | 1 | 停用 Nagle 演算法以合併發送封包。 |
| BsdUrgent | 2 | 使用 RFC-1222 定義的緊急資料。 |
| Expedited | 2 | 使用 RFC-1222 定義的快速資料。 |
| NoChecksum | 1 | 以校驗和為零傳送 UDP 資料報。 |
| ChecksumCoverage | 20 | 設定或取得 UDP 校驗和覆蓋範圍。 |
| UpdateAcceptContext | 28683 | 以監聽 socket 的相同屬性更新客戶端 socket。 |
| UpdateConnectContext | 28688 | 以監聽 socket 的相同屬性更新客戶端 socket。 |

## 另請參閱

* 命名空間 [System::Net::Sockets](../)
* 函式庫 [Aspose.Slides](../../)