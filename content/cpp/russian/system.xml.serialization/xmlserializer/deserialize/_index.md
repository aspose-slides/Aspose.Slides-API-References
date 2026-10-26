---
title: Deserialize()
second_title: Справочник API Aspose.Slides для C++
description: Десериализует XML-документ в объект.
type: docs
weight: 14
url: /ru/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) method


Десериализует XML-документ в объект.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток для чтения документа. |

### Возвращаемое значение

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) method


Десериализует XML-документ в объект.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Читатель для чтения документа. |

### Возвращаемое значение

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) method


Десериализует XML-документ в объект.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Читатель для чтения документа. |

### Возвращаемое значение

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) method


Десериализует XML-документ в объект.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Читатель для чтения документа. |
| encodingStyle | [String](../../../system/string/) | Стиль, использованный для сериализации объекта. |

### Возвращаемое значение

[Object](../../../system/object/) that was previously serialized into the document given.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlSerializer](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)