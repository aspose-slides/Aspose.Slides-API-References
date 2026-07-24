---
title: Evaluate()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XPath ifadesini değerlendirir ve tiplenmiş sonucu döndürür.
type: docs
weight: 807
url: /tr/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) yöntemi


Belirtilen [XPath](../../) ifadesini değerlendirir ve tiplenmiş sonucu döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Değerlendirilebilecek bir [XPath](../../) ifadesini temsil eden dize. |

### Dönüş Değeri

İfadenin sonucu ([Boolean](../../../system/boolean/), sayı, dize veya düğüm kümesi). Bu sırasıyla [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) veya [XPathNodeIterator](../../xpathnodeiterator/) nesnelerine karşılık gelir.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) yöntemi


Belirtilen [XPath](../../) ifadesini değerlendirir ve tiplenmiş sonucu döndürür, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak [XPath](../../) ifadesindeki ad alanı öneklerini çözer.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Değerlendirilebilecek bir [XPath](../../) ifadesini temsil eden dize. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [XPath](../../) ifadesindeki ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### Dönüş Değeri

İfadenin sonucu ([Boolean](../../../system/boolean/), sayı, dize veya düğüm kümesi). Bu sırasıyla [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) veya [XPathNodeIterator](../../xpathnodeiterator/) nesnelerine karşılık gelir.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) yöntemi


[XPathExpression](../../xpathexpression/) değerini değerlendirir ve tiplenmiş sonucu döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Değerlendirilebilecek bir [XPathExpression](../../xpathexpression/). |

### Dönüş Değeri

İfadenin sonucu ([Boolean](../../../system/boolean/), sayı, dize veya düğüm kümesi). Bu sırasıyla [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) veya [XPathNodeIterator](../../xpathnodeiterator/) nesnelerine karşılık gelir.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) yöntemi


Sağlanan bağlamı kullanarak [XPathExpression](../../xpathexpression/) ifadesini değerlendirir ve tiplenmiş sonucu döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Değerlendirilebilecek bir [XPathExpression](../../xpathexpression/). |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Değerlendirmenin yapılacağı seçili düğüm kümesini işaret eden bir [XPathNodeIterator](../../xpathnodeiterator/). |

### Dönüş Değeri

İfadenin sonucu ([Boolean](../../../system/boolean/), sayı, dize veya düğüm kümesi). Bu sırasıyla [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) veya [XPathNodeIterator](../../xpathnodeiterator/) nesnelerine karşılık gelir.

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [String](../../../system/string/)
* Sınıf [XPathNavigator](../)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Sınıf [XPathExpression](../../xpathexpression/)
* Sınıf [XPathNodeIterator](../../xpathnodeiterator/)
* Ad Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)