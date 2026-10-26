---
title: Select()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vybere množinu uzlů pomocí zadaného výrazu XPath.
type: docs
weight: 794
url: /cs/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) metoda

Vybere množinu uzlů pomocí zadaného [XPath](../../) výrazu.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) představující [XPath](../../) výraz. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) ukazující na vybranou množinu uzlů.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) metoda

Vybere množinu uzlů pomocí zadaného [XPath](../../) výrazu s objektem [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) určeným k rozlišení prefixů jmenných prostorů.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) představující [XPath](../../) výraz. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozlišení prefixů jmenných prostorů. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) ukazující na vybranou množinu uzlů.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) metoda

Vybere množinu uzlů pomocí zadaného [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) objekt obsahující zkompilovaný [XPath](../../) dotaz. |

### Návratová hodnota

[XPathNodeIterator](../../xpathnodeiterator/) ukazující na vybranou množinu uzlů.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathNodeIterator](../../xpathnodeiterator/)
* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XPathExpression](../../xpathexpression/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)