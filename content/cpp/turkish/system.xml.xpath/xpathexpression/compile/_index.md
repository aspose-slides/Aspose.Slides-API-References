---
title: Compile()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XPath ifadesini derler ve XPath ifadesini temsil eden bir XPathExpression nesnesi döndürür.
type: docs
weight: 66
url: /tr/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) metodu

Belirtilen [XPath](../../) ifadesini derler ve [XPath](../../) ifadesini temsil eden bir [XPathExpression](../) nesnesi döndürür.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Bir [XPath](../../) ifadesi. |

### Dönüş Değeri

Bir [XPathExpression](../) nesnesi.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) metodu

Belirtilen [XPath](../../) ifadesini, ad alanı çözümlemesi için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesiyle birlikte derler ve [XPath](../../) ifadesini temsil eden bir [XPathExpression](../) nesnesi döndürür.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Bir [XPath](../../) ifadesi. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ad alanı çözümlemesi için [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) arayüzünü uygulayan bir nesne. |

### Dönüş Değeri

Bir [XPathExpression](../) nesnesi.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XPathExpression](../)
* Sınıf [String](../../../system/string/)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Ad Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)