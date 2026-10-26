---
title: ReadNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein XmlNode-Objekt basierend auf den Informationen im XmlReader. Der Leser muss auf einem Knoten oder Attribut positioniert sein.
type: docs
weight: 495
url: /de/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) Methode

Erstellt ein [XmlNode](../../xmlnode/)-Objekt basierend auf den Informationen im [XmlReader](../../xmlreader/). Der Leser muss auf einem Knoten oder Attribut positioniert sein.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Die XML-Quelle. |

### Rückgabewert

Das neue [XmlNode](../../xmlnode/) oder **nullptr**, falls keine weiteren Knoten mehr existieren.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlReader](../../xmlreader/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)