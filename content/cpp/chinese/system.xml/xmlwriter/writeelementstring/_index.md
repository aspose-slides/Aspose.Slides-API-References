---
title: WriteElementString()
second_title: Aspose.Slides C++ API 参考
description: 写入具有指定本地名称和值的元素。
type: docs
weight: 443
url: /zh/system.xml/xmlwriter/writeelementstring/
---
## XmlWriter::WriteElementString(const String\&, const String\&) 方法

写入具有指定本地名称和值的元素。

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &localName, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |
| value | const [String](../../../system/string/)\& | 元素的值。 |

## XmlWriter::WriteElementString(const String\&, const String\&, const String\&) 方法

写入具有指定本地名称、命名空间 URI 和值的元素。

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &localName, const String &ns, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |
| ns | const [String](../../../system/string/)\& | 与元素关联的命名空间 URI。 |
| value | const [String](../../../system/string/)\& | 元素的值。 |

## XmlWriter::WriteElementString(const String\&, const String\&, const String\&, const String\&) 方法

写入具有指定前缀、本地名称、命名空间 URI 和值的元素。

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 元素的前缀。 |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |
| ns | const [String](../../../system/string/)\& | 元素的命名空间 URI。 |
| value | const [String](../../../system/string/)\& | 元素的值。 |

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)