---
title: BinaryWriter()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立 BinaryWriter 類別的實例，使用指定的編碼將資料寫入指定的串流。
type: docs
weight: 1
url: /zh-hant/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr&, const EncodingPtr&, bool) 建構函式

建立一個 [BinaryWriter](../) 類別的實例，使用指定的編碼將資料寫入指定的串流。

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)& | 輸出串流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | 要使用的編碼 |
| leaveopen | **bool** | 指定在目前的物件已解除配置後，是否應將串流 **stream** 保持開啟 (true) 或關閉 (false) |

## 另請參閱

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [BinaryWriter](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)