---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 118
url: /de/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) Methode

Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um den Unterbaum des angegebenen Knotens rekursiv zu klonen; **false**, um nur den Knoten selbst zu klonen. Bei Dokumenttyp-Knoten enthält der geklonte Knoten stets den Unterbaum, unabhängig von der Parametereinstellung. |

### Rückgabewert

Der geklonte Knoten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlDocumentType](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)