---
title: BeginSend()
second_title: Aspose.Slides for C++ API 參考
description: 發起非同步傳送操作。
type: docs
weight: 495
url: /zh-hant/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) 方法

發起非同步傳送操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用於讀取資料的緩衝區。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 從 'offset' 參數開始的指定陣列中的位元組數量。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時將被呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步傳送操作。 |

### 返回值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，表示已啟動的非同步傳送操作。

## 參見

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)