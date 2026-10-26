---
title: IsDerivedFrom()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen türetilmiş şema tipinin belirtilen temel şema tipinden türetilip türetilmediğini gösteren bir değer döndürür.
type: docs
weight: 209
url: /tr/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) metod

Belirtilen türetilmiş şema tipinin belirtilen temel şema tipinden türetilip türetilmediğini gösteren bir değer döndürür.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Test edilecek türetilmiş [XmlSchemaType](../). |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Test edilecek türetilmiş [XmlSchemaType](../) ile karşılaştırılacak temel [XmlSchemaType](../). |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Testten hariç tutmak için bir tip türetme yöntemi temsil eden XmlSchemaDerivationMethod değerlerinden biri. |

### Dönüş Değeri

**true** eğer türetilmiş tip temel tipten türetilmişse; aksi takdirde **false**.

## Bakınız

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchemaType](../)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)