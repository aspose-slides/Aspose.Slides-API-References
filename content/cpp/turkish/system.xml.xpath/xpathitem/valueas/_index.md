---
title: ValueAs()
second_title: C++ için Aspose.Slides API Referansı
description: Öğenin değerini belirtilen türde döndürür.
type: docs
weight: 131
url: /tr/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metodu


İtemin değerini belirtilen türde döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | İtem değerinin döndürüleceği tür. |

### Dönüş Değeri

İstenen türde öğenin değeri.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodu


Türetilmiş bir sınıfta geçersiz kılındığında, ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak belirtilen türde öğenin değerini döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | İtem değerinin döndürüleceği tür. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### Dönüş Değeri

İstenen türde öğenin değeri.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)