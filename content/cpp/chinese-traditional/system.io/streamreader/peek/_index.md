---
title: Peek()
second_title: Aspose.Slides for C++ API 參考
description: 從串流讀取單一字元，且不會改變串流的讀取游標。
type: docs
weight: 27
url: /zh-hant/system.io/streamreader/peek/
---
## StreamReader::Peek() 方法

從串流讀取單一字元，且不會改變串流的讀取游標。

```cpp
virtual int System::IO::StreamReader::Peek() override
```

### 返回值

讀取的字元以 UTF-16 編碼表示；如果讀取的字元在 UTF-16 編碼中由兩個代碼點組成，則只返回高位替代字元；如果未讀取到字元，則返回 -1

## 參見

* 類別 [StreamReader](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)