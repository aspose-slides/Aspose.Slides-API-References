---
title: CloneNode()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 92
url: /de/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) Methode


Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** um rekursiv den Unterbaum des angegebenen Knotens zu duplizieren; **false** um nur den Knoten selbst zu duplizieren. Für [XmlEntityReference](../)-Knoten gibt diese Methode stets einen Entitätsreferenzknoten ohne Kinder zurück. Der Ersatztext wird gesetzt, wenn der Knoten in ein übergeordnetes Element eingefügt wird. |

### Rückgabewert

Der duplizierte Knoten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlEntityReference](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)