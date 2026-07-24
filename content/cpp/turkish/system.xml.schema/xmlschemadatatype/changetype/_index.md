---
title: ChangeType()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değeri, türü XmlSchemaDatatype tarafından temsil edilen XML şema türünün geçerli temsillerinden biri olanı, belirtilen çalışma zamanı türüne dönüştürür.
type: docs
weight: 66
url: /tr/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) metodu


Belirtilen değeri, [XmlSchemaDatatype](../) tarafından temsil edilen XML şema türünün geçerli temsillerinden birinin türünde olanı, belirtilen çalışma zamanı türüne dönüştürür.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Belirtilen türe dönüştürülecek giriş değeri. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Giriş değerinin dönüştürüleceği hedef tür. |

### Dönüş Değeri

Dönüştürülmüş giriş değeri.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodu


Belirtilen değeri, [XmlSchemaDatatype](../) tarafından temsil edilen XML şema türünün geçerli temsillerinden birinin türünde olanı, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) kullanarak, [XmlSchemaDatatype](../) **xs:QName** türünü veya ondan türetilen bir türü temsil ediyorsa belirtilen çalışma zamanı türüne dönüştürür.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Belirtilen türe dönüştürülecek giriş değeri. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Giriş değerinin dönüştürüleceği hedef tür. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | ad alanı öneklerini çözümlemek için kullanılan bir [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/). Bu yalnızca [XmlSchemaDatatype](../) **xs:QName** türünü veya ondan türetilen bir türü temsil ediyorsa kullanışlıdır. |

### Dönüş Değeri

Dönüştürülmüş giriş değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)