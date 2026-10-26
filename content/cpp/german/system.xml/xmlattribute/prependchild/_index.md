---
title: PrependChild()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den angegebenen Knoten am Anfang der Liste der Kindknoten dieses Knotens ein.
type: docs
weight: 261
url: /de/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) Methode

Fügt den angegebenen Knoten am Anfang der Kindknotenliste dieses Knotens ein.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Das [XmlNode](../../xmlnode/) zum Hinzufügen. Wenn es ein [XmlDocumentFragment](../../xmldocumentfragment/) ist, wird der gesamte Inhalt des Dokumentfragments in die Kindliste dieses Knotens verschoben. |

### Rückgabewert

Das [XmlNode](../../xmlnode/) hinzugefügt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlAttribute](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)