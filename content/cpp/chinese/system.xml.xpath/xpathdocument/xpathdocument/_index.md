---
title: XPathDocument()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定 XmlReader 对象中包含的 XML 数据初始化 XPathDocument 类的新实例。
type: docs
weight: 1
url: /zh/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

初始化一个新的 [XPathDocument](../) 类实例，使用包含在指定的 [XmlReader](../../../system.xml/xmlreader/) 对象中的 XML 数据。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含 XML 数据的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

初始化一个新的 [XPathDocument](../) 类实例，使用包含在指定的 [XmlReader](../../../system.xml/xmlreader/) 对象中的 XML 数据，并使用指定的空白符处理方式。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含 XML 数据的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |
| space | [XmlSpace](../../../system.xml/xmlspace/) | 一个 XmlSpace 对象。 |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

初始化一个新的 [XPathDocument](../) 类实例，使用包含在指定的 TextReader 对象中的 XML 数据。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含 XML 数据的 TextReader 对象。 |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

初始化一个新的 [XPathDocument](../) 类实例，使用指定的 Stream 对象中的 XML 数据。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 数据的 Stream 对象。 |

## XPathDocument::XPathDocument(const String\&) constructor

初始化一个新的 [XPathDocument](../) 类实例，使用指定文件中的 XML 数据。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 包含 XML 数据的文件路径。 |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

初始化一个新的 [XPathDocument](../) 类实例，使用在指定文件中并按照指定的空白符处理方式读取的 XML 数据。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 包含 XML 数据的文件路径。 |
| space | [XmlSpace](../../../system.xml/xmlspace/) | 一个 XmlSpace 对象。 |

## 另见

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 类 [XPathDocument](../)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)