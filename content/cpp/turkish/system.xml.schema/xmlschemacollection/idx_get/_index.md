---
title: idx_get()
second_title: Aspose.Slides for C++ API Referansı
description: Verilen ad alanı URI'siyle ilişkili XmlSchema'ı döndürür.
type: docs
weight: 53
url: /tr/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metot

Verilen ad alanı URI'siyle ilişkili [XmlSchema](../../xmlschema/) döndürür.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Döndürmek istediğiniz şemanın ilişkili olduğu ad alanı URI'si. Bu genellikle şemanın **targetNamespace** özelliği olur. |

### Dönüş Değeri

[XmlSchema](../../xmlschema/)'ı ad alanı URI'siyle ilişkili olarak döndürür; verilen ad alanıyla ilişkili yüklenmiş bir şema yoksa ya da ad alanı bir XDR şemasıyla ilişkiliyse **nullptr** döndürür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../../xmlschema/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSchemaCollection](../)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)