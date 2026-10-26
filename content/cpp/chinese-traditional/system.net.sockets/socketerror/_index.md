---
title: SocketError
second_title: Aspose.Slides for C++ API 參考
description: 列舉套接字錯誤類型。
type: docs
weight: 209
url: /zh-hant/system.net.sockets/socketerror/
---
## SocketError 列舉

列舉套接字錯誤類型。

```cpp
enum class SocketError
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Success | 0 | 套接字操作成功完成。 |
| SocketError | -1 | 發生未指定的套接字錯誤。 |
| Interrupted | 10004 | 阻塞的套接字呼叫已被取消。 |
| AccessDenied | 10013 | 套接字的存取被拒絕。 |
| Fault | 10014 | 偵測到無效的指標位址。 |
| InvalidArgument | 10022 | 提供了無效的參數。 |
| TooManyOpenSockets | 10024 | 底層套接字提供者中開啟的套接字過多。 |
| WouldBlock | 10035 | 非阻塞套接字上無法立即完成操作。 |
| InProgress | 10036 | 阻塞操作正在進行中。 |
| AlreadyInProgress | 10037 | 非阻塞套接字已經有正在執行的操作。 |
| NotSocket | 10038 | 嘗試在非套接字上呼叫套接字操作。 |
| DestinationAddressRequired | 10039 | 套接字操作中遺漏了必要的位址。 |
| MessageSize | 10040 | 資料報文過長。 |
| ProtocolType | 10041 | 此套接字不支援此協定類型。 |
| ProtocolOption | 10042 | 使用了未知、無效或不支援的選項或層級。 |
| ProtocolNotSupported | 10043 | 協定未實作或未配置。 |
| SocketNotSupported | 10044 | 位址族群不支援指定的套接字。 |
| OperationNotSupported | 10045 | 協定族群不支援位址族群。 |
| ProtocolFamilyNotSupported | 10046 | 協定族群未實作或未配置。 |
| AddressFamilyNotSupported | 10047 | 指定的位址族群不受支援。 |
| AddressAlreadyInUse | 10048 | 位址只能使用一次。 |
| AddressNotAvailable | 10049 | 在此情境中選取的 IP 位址無效。 |
| NetworkDown | 10050 | 網路不可用。 |
| NetworkUnreachable | 10051 | 不存在到遠端主機的路由。 |
| NetworkReset | 10052 | 應用程式嘗試在已逾時的連線上設定「Keep-Alive」。 |
| ConnectionAborted | 10053 | 連線已中止。 |
| ConnectionReset | 10054 | 連線被遠端對等方重設。 |
| NoBufferSpaceAvailable | 10055 | 沒有可用的緩衝區空間供套接字操作使用。 |
| IsConnected | 10056 | 套接字已經連線。 |
| NotConnected | 10057 | 應用程式嘗試傳送或接收資料，但套接字未連線。 |
| Shutdown | 10058 | 因套接字已關閉，要求傳送或接收資料被禁止。 |
| TimedOut | 10060 | 連線嘗試逾時，或已連線的主機未回應。 |
| ConnectionRefused | 10061 | 遠端主機積極拒絕連線。 |
| HostDown | 10064 | 因遠端主機宕機而導致操作失敗。 |
| HostUnreachable | 10065 | 不存在到指定主機的網路路由。 |
| ProcessLimit | 10067 | 過多的程序正在使用底層套接字提供者。 |
| SystemNotReady | 10091 | 網路子系統不可用。 |
| VersionNotSupported | 10092 | 底層套接字提供者的版本超出範圍。 |
| NotInitialized | 10093 | 底層套接字提供者未初始化。 |
| Disconnecting | 10101 | 正在進行優雅的關閉。 |
| TypeNotFound | 10109 | 找不到指定的類別。 |
| HostNotFound | 11001 | 指定的主機未知。 |
| TryAgain | 11002 | 無法解析主機名稱。 |
| NoRecovery | 11003 | 錯誤不可恢復或找不到請求的資料庫。 |
| NoData | 11004 | 在名稱伺服器上找不到請求的名稱或 IP 位址。 |

## 另請參閱

* 命名空間 [System::Net::Sockets](../)
* 函式庫 [Aspose.Slides](../../)