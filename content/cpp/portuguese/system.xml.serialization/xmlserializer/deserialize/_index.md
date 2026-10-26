---
title: Deserialize()
second_title: Referência da API Aspose.Slides para C++
description: Desserializa documento XML em um objeto.
type: docs
weight: 14
url: /pt/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) método

Desserializa documento XML em um objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Stream para ler o documento. |

### Valor de Retorno

[Object](../../../system/object/) que foi previamente serializado no documento fornecido.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) método

Desserializa documento XML em um objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Leitor para ler o documento. |

### Valor de Retorno

[Object](../../../system/object/) que foi previamente serializado no documento fornecido.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) método

Desserializa documento XML em um objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Leitor para ler o documento. |

### Valor de Retorno

[Object](../../../system/object/) que foi previamente serializado no documento fornecido.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) método

Desserializa documento XML em um objeto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Leitor para ler o documento. |
| encodingStyle | [String](../../../system/string/) | Estilo usado para serializar o objeto. |

### Valor de Retorno

[Object](../../../system/object/) que foi previamente serializado no documento fornecido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../../../system.io/stream/)
* Classe [XmlSerializer](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)