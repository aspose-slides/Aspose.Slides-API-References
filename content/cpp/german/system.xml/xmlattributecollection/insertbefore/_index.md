---
title: InsertBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das angegebene Attribut sofort vor dem angegebenen Referenzattribut ein.
type: docs
weight: 53
url: /de/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) Methode


Fügt das angegebene Attribut unmittelbar vor dem angegebenen Referenzattribut ein.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Das Attribut, das eingefügt werden soll. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Das Referenzattribut. **newNode** wird vor dem **refNode** platziert. |

### Rückgabewert

Das [XmlAttribute](../../xmlattribute/) zum Einfügen in die Sammlung.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)