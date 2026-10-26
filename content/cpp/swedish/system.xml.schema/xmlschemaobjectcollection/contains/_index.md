---
title: Contains()
second_title: Aspose.Slides för C++ API-referens
description: Indikerar om den angivna XmlSchemaObject finns i XmlSchemaObjectCollection.
type: docs
weight: 92
url: /sv/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) metod


Anger om den angivna [XmlSchemaObject](../../xmlschemaobject/) finns i [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Den [XmlSchemaObject](../../xmlschemaobject/). |

### Returvärde

**true** om det specificerade kvalificerade namnet finns i samlingen; annars returneras **false**. Om **nullptr** tillhandahålls, returneras **false** eftersom det inte finns något kvalificerat namn med ett null-namn.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchemaObject](../../xmlschemaobject/)
* Klass [XmlSchemaObjectCollection](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)