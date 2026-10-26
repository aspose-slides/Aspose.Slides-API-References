---
title: BeginReceive()
second_title: Aspose.Slides for C++ API 參考
description: 初始化非同步寫入操作。
type: docs
weight: 521
url: /zh-hant/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) 方法

初始化非同步寫入操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收資料將被指派的緩衝區。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 從 `offset` 參數開始的指定陣列中位元組的數量。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時將被呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步接收操作。 |

### 傳回值

表示已啟動之非同步接收操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 相關參考

* 列舉 [SocketFlags](../../socketflags/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [Socket](../)
* 命名空間 [System::Net::Sockets](../../)
* 程式庫 [Aspose.Slides](../../../)