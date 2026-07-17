---
title: Serialize()
second_title: Aspose.Slides for C++ API 参考
description: 将文档序列化为 XML。
type: docs
weight: 27
url: /zh/system.xml.serialization/xmlserializer/serialize/
---
## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空间存储。 |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空间存储。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空间存储。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空间存储。 |
| encodingStyle | [String](../../../system/string/) | 序列化对象时使用的样式。 |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) method


将文档序列化为 XML。

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle, String id)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 目标流。 |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) to serialize. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 命名空间存储。 |
| encodingStyle | [String](../../../system/string/) | 序列化对象时使用的样式。 |
| id | [String](../../../system/string/) | [Object](../../../system/object/) id 在序列化时使用。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [Object](../../../system/object/)
* 类 [XmlSerializer](../)
* 类 [TextWriter](../../../system.io/textwriter/)
* 类 [XmlWriter](../../../system.xml/xmlwriter/)
* 类 [XmlSerializerNamespaces](../../xmlserializernamespaces/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::Serialization](../../)
* 库 [Aspose.Slides](../../../)