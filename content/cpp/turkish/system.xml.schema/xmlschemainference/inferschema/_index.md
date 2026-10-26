---
title: InferSchema()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XmlReader nesnesinde bulunan XML belgesinden bir XML Şema Tanım Dili (XSD) şeması çıkarır.
type: docs
weight: 66
url: /tr/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinde bulunan XML belgesinden bir XML [Schema](../../) Tanım Dili (XSD) şeması çıkarır.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) nesnesi, şema çıkarılacak XML belgesini içerir. |

### Dönüş Değeri

[XmlSchemaSet](../../xmlschemaset/) nesnesi, çıkarılan şemaları içerir.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinde bulunan XML belgesinden bir XML [Schema](../../) Tanım Dili (XSD) şeması çıkarır ve aynı hedef ad alanına sahip [XmlSchemaSet](../../xmlschemaset/) nesnesindeki mevcut şemayı kullanarak çıkarılan şemayı iyileştirir.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) nesnesi, şema çıkarılacak XML belgesini içerir. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | [XmlSchemaSet](../../xmlschemaset/) nesnesi, çıkarılan şemayı iyileştirmek için kullanılan mevcut bir şemayı içerir. |

### Dönüş Değeri

[XmlSchemaSet](../../xmlschemaset/) nesnesi, çıkarılan şemaları içerir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)