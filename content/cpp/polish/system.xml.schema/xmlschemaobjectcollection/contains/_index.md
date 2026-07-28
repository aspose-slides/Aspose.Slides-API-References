---
title: Contains()
second_title: Aspose.Slides for C++ – referencja API
description: Wskazuje, czy określony XmlSchemaObject znajduje się w XmlSchemaObjectCollection.
type: docs
weight: 92
url: /pl/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) method


Wskazuje, czy określony [XmlSchemaObject](../../xmlschemaobject/) znajduje się w [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Ten [XmlSchemaObject](../../xmlschemaobject/). |

### Wartość zwracana

**true** jeśli określona qualified name znajduje się w collection; w przeciwnym razie zwraca **false**. Jeśli podano **nullptr**, zwracane jest **false**, ponieważ nie ma qualified name o null name.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchemaObject](../../xmlschemaobject/)
* Klasa [XmlSchemaObjectCollection](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)