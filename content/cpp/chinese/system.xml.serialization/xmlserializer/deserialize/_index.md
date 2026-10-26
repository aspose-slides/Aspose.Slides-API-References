---
title: Deserialize()
second_title: Aspose.Slides for C++ API 参考
description: 将 XML 文档反序列化为对象。
type: docs
weight: 14
url: /zh/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) 方法

将 XML 文档反序列化为对象。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用于读取文档的流。 |

### 返回值

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) 方法

将 XML 文档反序列化为对象。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | 用于读取文档的读取器。 |

### 返回值

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) 方法

将 XML 文档反序列化为对象。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 用于读取文档的读取器。 |

### 返回值

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) 方法

将 XML 文档反序列化为对象。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 用于读取文档的读取器。 |
| encodingStyle | [String](../../../system/string/) | 用于序列化对象的样式。 |

### 返回值

[Object](../../../system/object/) that was previously serialized into the document given.

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Stream](../../../system.io/stream/)
* 类 [XmlSerializer](../)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)