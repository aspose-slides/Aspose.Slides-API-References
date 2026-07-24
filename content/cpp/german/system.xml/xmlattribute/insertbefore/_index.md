---
title: InsertBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den angegebenen Knoten unmittelbar vor dem angegebenen Referenzknoten ein.
type: docs
weight: 209
url: /de/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) Methode

Fügt den angegebenen Knoten unmittelbar vor dem angegebenen Referenzknoten ein.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Das [XmlNode](../../xmlnode/) zum Einfügen. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Der [XmlNode](../../xmlnode/), der der Referenzknoten ist. Der **newChild** wird vor diesem Knoten platziert. |

### Rückgabewert

Der [XmlNode](../../xmlnode/) eingefügt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlAttribute](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)