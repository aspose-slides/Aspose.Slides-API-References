---
title: EndSend()
second_title: Aspose.Slides for C++ API 參考
description: 等待直到指定的非同步傳送操作完成。
type: docs
weight: 508
url: /zh-hant/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) 方法

等待直到指定的非同步傳送操作完成。

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示非同步傳送操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 傳回值

已傳送的位元組數。

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) 方法

等待直到指定的非同步傳送操作完成。

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示非同步傳送操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |
| errorCode | [SocketError](../../socketerror/)\& | 當傳送操作失敗時，錯誤代碼將指派至此輸出參數。 |

### 傳回值

已傳送的位元組數。

## 參見

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)