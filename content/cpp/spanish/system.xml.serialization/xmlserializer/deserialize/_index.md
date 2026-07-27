---
title: Deserialize()
second_title: Referencia de la API de Aspose.Slides para C++
description: Deserializa un documento XML en un objeto.
type: docs
weight: 14
url: /es/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) método


Deserializa un documento XML en un objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Flujo para leer el documento. |

### Valor devuelto

[Object](../../../system/object/) que fue previamente serializado en el documento dado.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) método


Deserializa un documento XML en un objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Lector para leer el documento. |

### Valor devuelto

[Object](../../../system/object/) que fue previamente serializado en el documento dado.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) método


Deserializa un documento XML en un objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Lector para leer el documento. |

### Valor devuelto

[Object](../../../system/object/) que fue previamente serializado en el documento dado.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) método


Deserializa un documento XML en un objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Lector para leer el documento. |
| encodingStyle | [String](../../../system/string/) | Estilo usado para serializar el objeto. |

### Valor devuelto

[Object](../../../system/object/) que fue previamente serializado en el documento dado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Stream](../../../system.io/stream/)
* Clase [XmlSerializer](../)
* Clase [TextReader](../../../system.io/textreader/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::Serialization](../../)
* Biblioteca [Aspose.Slides](../../../)