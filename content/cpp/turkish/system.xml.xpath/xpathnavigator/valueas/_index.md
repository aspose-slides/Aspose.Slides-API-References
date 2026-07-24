---
title: ValueAs()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen IXmlNamespaceResolver nesnesini kullanarak, geçerli düğümün değerini Type olarak döndürür, ad alanı öneklerini çözmek için.
type: docs
weight: 378
url: /tr/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) yöntem

Belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak, geçerli düğümün değerini belirtilen Tür olarak döndürür, ad alanı öneklerini çözmek için.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Geçerli düğümün değerini bu Tür olarak döndürmek için. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi, ad alanı öneklerini çözmek için kullanılır. |

### Dönüş Değeri

İstenen Türde, geçerli düğümün değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Sınıf [XPathNavigator](../)
* Ad Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)