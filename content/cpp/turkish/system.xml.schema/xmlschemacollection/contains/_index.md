---
title: Contains()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XmlSchema'ın targetNamespace değerinin koleksiyon içinde olup olmadığını gösteren bir değer döndürür.
type: docs
weight: 66
url: /tr/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) metot


Belirtilen [XmlSchema](../../xmlschema/)'in **targetNamespace** değerinin koleksiyon içinde olup olmadığını gösteren bir değer döndürür.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) nesnesi. |

### Dönüş Değeri

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## XmlSchemaCollection::Contains(const String\&) metot


Belirtilen ad alanına sahip bir şemanın koleksiyon içinde olup olmadığını gösteren bir değer döndürür.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Şema ile ilişkili ad alanı URI'si. XML Şemaları için bu genellikle hedef ad alanı olur. |

### Dönüş Değeri

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../../xmlschema/)
* Sınıf [XmlSchemaCollection](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)