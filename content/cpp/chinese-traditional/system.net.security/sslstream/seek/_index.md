---
title: Seek()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定目前物件所代表的串流位置。
type: docs
weight: 365
url: /zh-hant/system.net.security/sslstream/seek/
---
## SslStream::Seek(int64_t, IO::SeekOrigin) method

設定目前物件所代表的串流位置。

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 指定之位置的位元組偏移量 |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | 指定偏移量計算的起始位置與方向 |

### 傳回值

串流的新位置

## 另請參閱

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* 類別 [SslStream](../)
* 命名空間 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)