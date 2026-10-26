---
title: PeekChar()
second_title: Aspose.Slides for C++ API 參考
description: 從輸入流讀取單一字符而不更改流的讀取游標。
type: docs
weight: 53
url: /zh-hant/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() 方法

從輸入流讀取單一字符而不更改流的讀取游標。

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### 返回值

以 UTF-16 編碼的讀取字符；如果該字符在 UTF-16 編碼中由兩個碼點表示，則僅返回高代理區；如果未讀取到字符，則返回 -1

## 另見

* 類別 [BinaryReader](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)