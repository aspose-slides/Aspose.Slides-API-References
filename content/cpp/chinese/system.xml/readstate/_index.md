---
title: ReadState
second_title: Aspose.Slides for C++ API 参考
description: 指定读取器的状态。
type: docs
weight: 703
url: /zh/system.xml/readstate/
---
## ReadState 枚举


指定读取器的状态。

```cpp
enum class ReadState
```

### 值

| Name | Value | Description |
| --- | --- | --- |
| Initial | 0 | 尚未调用 [XmlReader::Read](../xmlreader/read/) 方法。 |
| Interactive | 1 | 已经调用了 [XmlReader::Read](../xmlreader/read/) 方法。可以在读取器上调用其他方法。 |
| Error | 2 | 发生错误，导致读取操作无法继续。 |
| EndOfFile | 3 | 已成功到达文件末尾。 |
| Closed | 4 | 已经调用了 [XmlReader::Close](../xmlreader/close/) 方法。 |

## 另见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)