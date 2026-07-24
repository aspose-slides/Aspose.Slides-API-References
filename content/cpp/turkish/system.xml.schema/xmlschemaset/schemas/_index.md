---
title: Schemas()
second_title: Aspose.Slides for C++ API Referansı
description: XmlSchemaSet içindeki tüm XML Şema tanım dili (XSD) şemalarının bir koleksiyonunu döndürür.
type: docs
weight: 248
url: /tr/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() yöntemi

[XmlSchemaSet](../) içinde bulunan tüm XML [Schema](../../) tanım dili (XSD) şemalarının bir koleksiyonunu döndürür.

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Dönüş Değeri

[XmlSchemaSet](../)'ye eklenmiş tüm şemaları içeren bir IList nesnesi. [XmlSchemaSet](../)'ye hiçbir şema eklenmemişse, boş bir koleksiyon döndürülür.

## XmlSchemaSet::Schemas(String) yöntemi

Verilen ad alanına ait [XmlSchemaSet](../) içinde bulunan tüm XML [Schema](../../) tanım dili (XSD) şemalarının bir koleksiyonunu döndürür.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Şemanın **targetNamespace** özelliği. |

### Dönüş Değeri

[XmlSchemaSet](../)'ye eklenmiş ve verilen ad alanına ait tüm şemaları içeren bir IList nesnesi. [XmlSchemaSet](../)'ye hiçbir şema eklenmemişse, boş bir koleksiyon döndürülür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)