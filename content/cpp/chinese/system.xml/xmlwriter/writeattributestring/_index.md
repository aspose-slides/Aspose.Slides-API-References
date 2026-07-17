---
title: WriteAttributeString()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中被覆盖时，写入具有指定本地名称、命名空间 URI 和数值的属性。
type: docs
weight: 131
url: /zh/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) method

当在派生类中被覆盖时，写入具有指定本地名称、命名空间 URI 和值的属性。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| ns | const [String](../../../system/string/)\& | 与属性关联的命名空间 URI。 |
| value | const [String](../../../system/string/)\& | 属性的值。 |

## XmlWriter::WriteAttributeString(const String\&, const String\&) method

当在派生类中被覆盖时，写出具有指定本地名称和值的属性。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| value | const [String](../../../system/string/)\& | 属性的值。 |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) method

当在派生类中被覆盖时，写出具有指定前缀、本地名称、命名空间 URI 和值的属性。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 属性的命名空间前缀。 |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| ns | const [String](../../../system/string/)\& | 属性的命名空间 URI。 |
| value | const [String](../../../system/string/)\& | 属性的值。 |

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)