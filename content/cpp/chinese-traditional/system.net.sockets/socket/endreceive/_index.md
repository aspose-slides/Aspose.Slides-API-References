---
title: EndReceive()
second_title: Aspose.Slides for C++ API 參考文件
description: 等待指定的非同步接收作業完成。
type: docs
weight: 534
url: /zh-hant/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的非同步接收作業完成。

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 代表非同步接收作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 傳回值

已接收的位元組數。

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) 方法

等待指定的非同步接收作業完成。

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 代表非同步接收作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |
| errorCode | [SocketError](../../socketerror/)\& | 當接收作業失敗時，錯誤代碼會指派給此輸出參數。 |

### 傳回值

已接收的位元組數。

## 另請參閱

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)