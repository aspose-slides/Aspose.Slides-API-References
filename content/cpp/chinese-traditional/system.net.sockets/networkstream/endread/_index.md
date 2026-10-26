---
title: EndRead()
second_title: Aspose.Slides for C++ API 參考
description: 等待指定的非同步讀取作業完成。
type: docs
weight: 261
url: /zh-hant/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) method


等待指定的非同步讀取作業完成。

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示非同步讀取作業的 [IAsyncResult](../../../system/iasyncresult/) 物件 |

### 傳回值

在由 **asyncResult** 表示的讀取作業期間讀取的位元組數

## 相關參考

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [NetworkStream](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)