---
title: InsertAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das angegebene Attribut unmittelbar nach dem angegebenen Referenzattribut ein.
type: docs
weight: 66
url: /de/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) Methode


Fügt das angegebene Attribut unmittelbar nach dem angegebenen Referenzattribut ein.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Das einzufügende Attribut. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Das Referenzattribut. **newNode** wird nach dem **refNode** platziert. |

### Rückgabewert

Das [XmlAttribute](../../xmlattribute/) zum Einfügen in die Sammlung.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)