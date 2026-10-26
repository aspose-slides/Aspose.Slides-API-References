---
title: Contains()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XmlSchemaObject'in XmlSchemaObjectCollection içinde olup olmadığını gösterir.
type: docs
weight: 92
url: /tr/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) method


Belirtilen [XmlSchemaObject](../../xmlschemaobject/)'nin [XmlSchemaObjectCollection](../) içinde olup olmadığını gösterir.

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Belirtilen [XmlSchemaObject](../../xmlschemaobject/). |

### Dönüş Değeri

**true** if the specified qualified name is in the collection; otherwise, returns **false**. If **nullptr** is supplied, **false** is returned because there is no qualified name with a null name.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchemaObject](../../xmlschemaobject/)
* Sınıf [XmlSchemaObjectCollection](../)
* Ad alanı [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)