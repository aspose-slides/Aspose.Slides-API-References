---
title: ReadState
second_title: Aspose.Slides C++ API 參考
description: 指定讀取器的狀態。
type: docs
weight: 703
url: /zh-hant/system.xml/readstate/
---
## ReadState 列舉

指定讀取器的狀態。

```cpp
enum class ReadState
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Initial | 0 | 尚未呼叫 [XmlReader::Read](../xmlreader/read/) 方法。 |
| Interactive | 1 | 已呼叫 [XmlReader::Read](../xmlreader/read/) 方法。可以對讀取器呼叫其他方法。 |
| Error | 2 | 發生錯誤，導致讀取操作無法繼續。 |
| EndOfFile | 3 | 已成功到達檔案結尾。 |
| Closed | 4 | 已呼叫 [XmlReader::Close](../xmlreader/close/) 方法。 |

## See Also

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)