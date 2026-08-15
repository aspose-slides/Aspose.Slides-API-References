---
title: EndRead()
second_title: Aspose.Slides for C++ API 參考
description: 等待直到指定的非同步讀取操作完成。
type: docs
weight: 183
url: /zh-hant/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) 方法


等待直到指定的非同步讀取操作完成。

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | 表示非同步讀取操作的 [IAsyncResult](../../../system/iasyncresult/) 物件 |

### 返回值

在由 **asyncResult** 所表示的讀取操作期間讀取的位元組數

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)