---
title: EndRead()
second_title: Aspose.Slides for C++ API 參考
description: 等待直到指定的非同步讀取作業完成。
type: docs
weight: 430
url: /zh-hant/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) 方法

等待直到指定的非同步讀取作業完成。

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示非同步讀取作業的 [IAsyncResult](../../../system/iasyncresult/) 物件 |

### 傳回值

由 **asyncResult** 表示的讀取作業期間讀取的位元組數

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [SslStream](../)
* 命名空間 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)