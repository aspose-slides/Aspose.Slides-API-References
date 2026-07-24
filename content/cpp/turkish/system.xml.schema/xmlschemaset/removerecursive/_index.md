---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XML Şema tanım dili (XSD) şemasını ve XmlSchemaSet'ten içe aktardığı tüm şemaları kaldırır.
type: docs
weight: 183
url: /tr/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) method

Belirtilen XML [Schema](../../) tanım dili (XSD) şemasını ve [XmlSchemaSet](../) tarafından içe aktarılan tüm şemaları kaldırır.

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) nesnesi [XmlSchemaSet](../) üzerinden kaldırmak için. |

### Dönüş Değeri

**true** eğer [XmlSchema](../../xmlschema/) nesnesi ve tüm içe aktarımları başarıyla kaldırıldıysa; aksi takdirde, **false**.

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../../xmlschema/)
* Sınıf [XmlSchemaSet](../)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)