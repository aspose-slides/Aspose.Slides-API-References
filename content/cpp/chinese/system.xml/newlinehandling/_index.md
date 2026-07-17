---
title: NewLineHandling
second_title: Aspose.Slides for C++ API 参考
description: 指定如何处理换行符。
type: docs
weight: 690
url: /zh/system.xml/newlinehandling/
---
## NewLineHandling 枚举

指定如何处理换行符。

```cpp
enum class NewLineHandling
```

### 值

| Name | Value | Description |
| --- | --- | --- |
| Replace | 0 | 换行字符将被替换，以匹配 [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) 值中指定的字符。 |
| Entitize | 1 | 换行字符将被实体化。此设置在输出被标准化的 [XmlReader](../xmlreader/) 读取时可保留所有字符。 |
| None | 2 | 换行字符保持不变。输出与输入相同。 |

## 另请参阅

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)