---
title: Serialize()
second_title: Aspose.Slides for C++ API 參考
description: 將文件序列化為 XML。
type: docs
weight: 27
url: /zh-hant/system.xml.serialization/xmlserializer/serialize/
---
## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |

## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空間儲存。 |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空間儲存。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空間儲存。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空間儲存。 |
| encodingStyle | [String](../../../system/string/) | 序列化物件時使用的樣式。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) 方法

將文件序列化為 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle, String id)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目標串流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 進行序列化。 |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空間儲存。 |
| encodingStyle | [String](../../../system/string/) | 序列化物件時使用的樣式。 |
| id | [String](../../../system/string/) | [Object](../../../system/object/) id 用於序列化時的 id。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Object](../../../system/object/)
* Class [XmlSerializer](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XmlSerializerNamespaces](../../xmlserializernamespaces/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)