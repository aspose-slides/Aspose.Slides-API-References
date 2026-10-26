---
title: WriteStartAttribute()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的本地名称和命名空间 URI 写入属性的起始标记。
type: docs
weight: 144
url: /zh/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) method

写入具有指定本地名称和命名空间 URI 的属性起始标记。

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| ns | const [String](../../../system/string/)\& | 属性的命名空间 URI。 |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) method

在派生类中被重写时，写入具有指定前缀、本地名称和命名空间 URI 的属性起始标记。

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 属性的命名空间前缀。 |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| ns | const [String](../../../system/string/)\& | 属性的命名空间 URI。 |

## XmlWriter::WriteStartAttribute(const String\&) method

写入具有指定本地名称的属性起始标记。

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)