---
title: Reprocess()
second_title: Aspose.Slides for C++ API Referansı
description: XmlSchemaSet içinde zaten bulunan bir XML Şema tanım dili (XSD) şemasını yeniden işler.
type: docs
weight: 222
url: /tr/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metodu


XML [Schema](../../) tanım dili (XSD) şemasını, zaten [XmlSchemaSet](../) içinde bulunanı yeniden işler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Yeniden işlenecek şema. |

### Dönüş Değeri

[XmlSchema](../../xmlschema/) nesnesi, şema geçerli bir şema ise. Şema geçerli değilse ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde, bir XmlSchemaException fırlatılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../../xmlschema/)
* Sınıf [XmlSchemaSet](../)
* Ad alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)