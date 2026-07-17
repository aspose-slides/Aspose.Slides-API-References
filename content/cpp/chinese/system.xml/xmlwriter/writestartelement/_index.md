---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中被覆盖时，写入指定的开始标签并将其与给定的命名空间关联。
type: docs
weight: 92
url: /zh/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) 方法

当在派生类中被覆盖时，写入指定的开始标签并将其关联到给定的命名空间。

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |
| ns | const [String](../../../system/string/)\& | 要与元素关联的命名空间 URI。如果此命名空间已经在作用域中并且已有关联的前缀，写入器会自动写入该前缀。 |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) 方法

当在派生类中被覆盖时，写入指定的开始标签并将其关联到给定的命名空间和前缀。

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 元素的命名空间前缀。 |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |
| ns | const [String](../../../system/string/)\& | 要与元素关联的命名空间 URI。 |

## XmlWriter::WriteStartElement(const String\&) 方法

当在派生类中被覆盖时，写出具有指定本地名称的开始标签。

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)