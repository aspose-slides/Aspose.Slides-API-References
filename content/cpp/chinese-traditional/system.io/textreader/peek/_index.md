---
title: Peek()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 從串流中讀取單個字符，且不會更改串流的讀取指標。
type: docs
weight: 27
url: /zh-hant/system.io/textreader/peek/
---
## TextReader::Peek() method


從串流中讀取單個字符，且不會改變串流的讀取指標。

```cpp
virtual int System::IO::TextReader::Peek()
```


### 返回值

讀取的字符以 UTF-16 編碼；如果讀取的字符在 UTF-16 中由兩個碼位表示，則僅返回高位代理項；若未讀取到字符，則返回 -1

## 另請參閱

* 類別 [TextReader](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)