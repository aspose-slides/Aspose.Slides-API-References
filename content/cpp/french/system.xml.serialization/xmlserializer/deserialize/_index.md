---
title: Deserialize()
second_title: Référence de l'API Aspose.Slides pour C++
description: Désérialise le document XML en un objet.
type: docs
weight: 14
url: /fr/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) méthode

Désérialise le document XML en un objet.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Flux à partir duquel lire le document. |

### Valeur de retour

[Object](../../../system/object/) qui a été préalablement sérialisé dans le document donné.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) méthode

Désérialise le document XML en un objet.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Lecteur à partir duquel lire le document. |

### Valeur de retour

[Object](../../../system/object/) qui a été préalablement sérialisé dans le document donné.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) méthode

Désérialise le document XML en un objet.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Lecteur à partir duquel lire le document. |

### Valeur de retour

[Object](../../../system/object/) qui a été préalablement sérialisé dans le document donné.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) méthode

Désérialise le document XML en un objet.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Lecteur à partir duquel lire le document. |
| encodingStyle | [String](../../../system/string/) | Style utilisé pour sérialiser l'objet. |

### Valeur de retour

[Object](../../../system/object/) qui a été préalablement sérialisé dans le document donné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../../../system.io/stream/)
* Classe [XmlSerializer](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::Serialization](../../)
* Bibliothèque [Aspose.Slides](../../../)