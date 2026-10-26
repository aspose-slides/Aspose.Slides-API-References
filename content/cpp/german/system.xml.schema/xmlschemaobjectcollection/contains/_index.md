---
title: Contains()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob das angegebene XmlSchemaObject in der XmlSchemaObjectCollection enthalten ist.
type: docs
weight: 92
url: /de/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) Methode


Gibt an, ob das angegebene [XmlSchemaObject](../../xmlschemaobject/) in der [XmlSchemaObjectCollection](../) enthalten ist.

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Das [XmlSchemaObject](../../xmlschemaobject/). |

### Rückgabewert

**true** wenn der angegebene qualifizierte Name in der Sammlung ist; andernfalls wird **false** zurückgegeben. Wenn **nullptr** übergeben wird, wird **false** zurückgegeben, weil es keinen qualifizierten Namen mit einem Nullnamen gibt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaObject](../../xmlschemaobject/)
* Klasse [XmlSchemaObjectCollection](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)