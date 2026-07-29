---
title: Evaluate()
second_title: Aspose.Slides för C++ API-referens
description: Utvärderar det angivna XPath-uttrycket och returnerar det typade resultatet.
type: docs
weight: 807
url: /sv/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) metod


Utvärderar det angivna [XPath](../../)-uttrycket och returnerar det typade resultatet.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | En sträng som representerar ett [XPath](../../)-uttryck som kan utvärderas. |

### Returvärde

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller nodmängd). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/)-objekt respektive.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) metod


Utvärderar det angivna [XPath](../../)-uttrycket och returnerar det typade resultatet, med hjälp av det angivna [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprrefix i [XPath](../../)-uttrycket.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | En sträng som representerar ett [XPath](../../)-uttryck som kan utvärderas. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objekt som används för att lösa namnrymdsprrefix i [XPath](../../)-uttrycket. |

### Returvärde

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller nodmängd). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/)-objekt respektive.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) metod


Utvärderar [XPathExpression](../../xpathexpression/) och returnerar det typade resultatet.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ett [XPathExpression](../../xpathexpression/) som kan utvärderas. |

### Returvärde

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller nodmängd). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/)-objekt respektive.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) metod


Använder den tillhandahållna kontexten för att utvärdera [XPathExpression](../../xpathexpression/) och returnerar det typade resultatet.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ett [XPathExpression](../../xpathexpression/) som kan utvärderas. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Ett [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda nodmängden som utvärderingen ska utföras på. |

### Returvärde

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller nodmängd). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/)-objekt respektive.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klass [XPathExpression](../../xpathexpression/)
* Klass [XPathNodeIterator](../../xpathnodeiterator/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)