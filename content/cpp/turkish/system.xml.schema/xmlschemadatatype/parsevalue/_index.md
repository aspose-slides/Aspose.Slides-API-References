---
title: ParseValue()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyi yerleşik veya kullanıcı tanımlı bir basit türe karşı doğrular.
type: docs
weight: 53
url: /tr/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) metot


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen **string**i yerleşik veya kullanıcı tanımlı bir basit türe karşı doğrular.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | [String](../../../system/string/) | Basit türe karşı doğrulamak için **string**. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Bu [XmlSchemaDatatype](../) nesnesi **xs:NCName** tipini temsil ediyorsa, **string**i ayrıştırırken atomizasyon için kullanılacak [XmlNameTable](../../../system.xml/xmlnametable/). |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Bu [XmlSchemaDatatype](../) nesnesi **xs:QName** tipini temsil ediyorsa, **string**i ayrıştırırken kullanılacak [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### Dönüş Değeri

[Object](../../../system/object/) nesnesi, [XmlSchemaDatatype::get_ValueType](../get_valuetype/) çağrısı tarafından döndürülen türe güvenli bir şekilde dönüştürülebilir.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNameTable](../../../system.xml/xmlnametable/)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Sınıf [XmlSchemaDatatype](../)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)