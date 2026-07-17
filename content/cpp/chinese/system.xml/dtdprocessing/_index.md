---
title: DtdProcessing
second_title: Aspose.Slides for C++ API 参考
description: 指定处理 DTD 的选项。DtdProcessing 枚举由 XmlReaderSettings 类使用。
type: docs
weight: 638
url: /zh/system.xml/dtdprocessing/
---
## DtdProcessing 枚举

指定处理 DTD 的选项。DtdProcessing 枚举由 [XmlReaderSettings](../xmlreadersettings/) 类使用。

```cpp
enum class DtdProcessing
```

### 取值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Prohibit | 0 | 指定当遇到 DTD 时，会抛出 XmlException，消息说明 DTD 被禁止。这是默认行为。 |
| Ignore | 1 | 导致 DOCTYPE 元素被忽略。不会进行 DTD 处理，且 DTD/DOCTYPE 在输出时丢失。 |
| Parse | 2 | 用于解析 DTD。 |

## 另请参阅

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)