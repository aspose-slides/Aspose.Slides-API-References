---
title: Seek()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定目前物件所代表的串流位置。
type: docs
weight: 183
url: /zh-hant/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) 方法


設定目前物件所代表的串流位置。

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 所指定位置的位元組偏移量 |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | 指定計算偏移量的起始位置與方向 |

### 返回值

串流的新位置

## 參見

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)