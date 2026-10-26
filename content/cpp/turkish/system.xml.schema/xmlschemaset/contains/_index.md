---
title: Contains()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen hedef ad alanı URI'sine sahip bir XML Şema tanım dili (XSD) şemasının XmlSchemaSet içinde olup olmadığını gösterir.
type: docs
weight: 196
url: /tr/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metodu


Belirtilen hedef ad alanı URI'sine sahip bir XML [Schema](../../) tanım dili (XSD) şemasının [XmlSchemaSet](../) içinde olup olmadığını gösterir.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Şemanın **targetNamespace** özelliği. |

### Dönüş Değeri

**true** eğer belirtilen hedef ad alanı URI'sine sahip bir şema [XmlSchemaSet](../) içinde ise; aksi takdirde **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metodu


Belirtilen XML [Schema](../../) tanım dili (XSD) [XmlSchema](../../xmlschema/) nesnesinin [XmlSchemaSet](../) içinde olup olmadığını gösterir.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) nesnesi. |

### Dönüş Değeri

**true** eğer [XmlSchema](../../xmlschema/) nesnesi [XmlSchemaSet](../) içinde ise; aksi takdirde **false**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSchemaSet](../)
* Sınıf [XmlSchema](../../xmlschema/)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)