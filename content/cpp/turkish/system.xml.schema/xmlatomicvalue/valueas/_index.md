---
title: ValueAs()
second_title: Aspose.Slides for C++ API Referansı
description: Doğrulanan XML öğesinin veya niteliğin değerini, ad alanı öneklerini çözümlemek için belirtilen IXmlNamespaceResolver nesnesi kullanılarak belirtilen türe döndürür.
type: docs
weight: 144
url: /tr/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodu

Doğrulanan XML öğesinin veya niteliğin değerini, ad alanı öneklerini çözümlemek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi kullanılarak belirtilen türe döndürür.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Doğrulanan XML öğesinin veya niteliğin değerinin döndürüleceği tür. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi, ad alanı öneklerini çözümlemek için kullanılır. |

### Dönüş Değeri

İstenen türde, doğrulanan XML öğesinin veya niteliğin değeri.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Sınıf [XmlAtomicValue](../)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)