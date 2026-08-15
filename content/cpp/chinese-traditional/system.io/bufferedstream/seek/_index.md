---
title: Seek()
second_title: Aspose.Slides C++ API 參考
description: 設定目前物件所代表的串流位置。
type: docs
weight: 79
url: /zh-hant/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) 方法


設定目前物件所代表的串流位置。

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 指定之位置的位元組偏移量 |
| origin | [SeekOrigin](../../seekorigin/) | 指定計算偏移量之起始位置與方向 |

### 回傳值

串流的新位置

## 另請參閱

* Enum [SeekOrigin](../../seekorigin/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)