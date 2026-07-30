---
title: Deserialize()
second_title: Riferimento API Aspose.Slides per C++
description: Deserializza il documento XML in un oggetto.
type: docs
weight: 14
url: /it/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) metodo


Deserializza il documento XML in un oggetto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Flusso da cui leggere il documento. |

### Valore restituito

[Object](../../../system/object/) che era stato precedentemente serializzato nel documento fornito.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) metodo


Deserializza il documento XML in un oggetto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Lettore da cui leggere il documento. |

### Valore restituito

[Object](../../../system/object/) che era stato precedentemente serializzato nel documento fornito.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) metodo


Deserializza il documento XML in un oggetto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Lettore da cui leggere il documento. |

### Valore restituito

[Object](../../../system/object/) che era stato precedentemente serializzato nel documento fornito.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) metodo


Deserializza il documento XML in un oggetto.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Lettore da cui leggere il documento. |
| encodingStyle | [String](../../../system/string/) | Stile usato per serializzare l'oggetto. |

### Valore restituito

[Object](../../../system/object/) che era stato precedentemente serializzato nel documento fornito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../../../system.io/stream/)
* Classe [XmlSerializer](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)