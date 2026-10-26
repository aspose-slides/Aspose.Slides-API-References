---
title: Select()
second_title: Aspose.Slides C++ API Referencia
description: Kiválaszt egy csomópontkészletet a megadott XPath kifejezéssel.
type: docs
weight: 794
url: /hu/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) metódus

Kiválaszt egy csomópontkészletet a megadott [XPath](../../) kifejezéssel.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Egy [String](../../../system/string/) amely egy [XPath](../../) kifejezést képvisel. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/), amely a kiválasztott csomópontkészletre mutat.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) metódus

A megadott [XPath](../../) kifejezéssel és a névtér-előtagok feloldásához megadott [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektummal kiválaszt egy csomópontkészletet.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Egy [String](../../../system/string/) amely egy [XPath](../../) kifejezést képvisel. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | A [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a névtér-előtagok feloldására szolgál. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/), amely a kiválasztott csomópontkészletre mutat.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) metódus

A megadott [XPathExpression](../../xpathexpression/) használatával kiválaszt egy csomópontkészletet.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Egy [XPathExpression](../../xpathexpression/) objektum, amely a lefordított [XPath](../../) lekérdezést tartalmazza. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/), amely a kiválasztott csomópontkészletre mutat.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathNodeIterator](../../xpathnodeiterator/)
* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Osztály [XPathExpression](../../xpathexpression/)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)