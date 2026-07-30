---
title: Contains()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje, zda je zadaný XmlSchemaObject v XmlSchemaObjectCollection.
type: docs
weight: 92
url: /cs/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) metoda

Určuje, zda je zadaný [XmlSchemaObject](../../xmlschemaobject/) v [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Zadaný [XmlSchemaObject](../../xmlschemaobject/). |

### Návratová hodnota

**true** pokud je zadaný kvalifikovaný název v kolekci; jinak vrací **false**. Pokud je zadáno **nullptr**, vrací se **false**, protože neexistuje kvalifikovaný název s nulovým názvem.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [XmlSchemaObject](../../xmlschemaobject/)
* třída [XmlSchemaObjectCollection](../)
* jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)