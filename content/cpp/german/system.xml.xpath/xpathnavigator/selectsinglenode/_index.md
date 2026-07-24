---
title: SelectSingleNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt einen einzelnen Knoten im XPathNavigator mit der angegebenen XPath-Abfrage aus.
type: docs
weight: 781
url: /de/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) Methode

Wählt einen einzelnen Knoten im [XPathNavigator](../) mit der angegebenen [XPath](../../)-Abfrage aus.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ein [String](../../../system/string/), das einen [XPath](../../)-Ausdruck darstellt. |

### Rückgabewert

Ein [XPathNavigator](../)-Objekt, das den ersten passenden Knoten für die angegebene [XPath](../../)-Abfrage enthält; andernfalls **nullptr**, wenn es keine Abfrageergebnisse gibt.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) Methode

Wählt einen einzelnen Knoten im [XPathNavigator](../)-Objekt aus, indem die angegebene [XPath](../../)-Abfrage zusammen mit dem angegebenen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt verwendet wird, um Namensraum-Präfixe aufzulösen.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ein [String](../../../system/string/), der einen [XPath](../../)-Ausdruck darstellt. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zum Auflösen von Namensraum-Präfixen in der [XPath](../../)-Abfrage verwendet wird. |

### Rückgabewert

Ein [XPathNavigator](../)-Objekt, das den ersten passenden Knoten für die angegebene [XPath](../../)-Abfrage enthält; andernfalls **nullptr**, wenn es keine Abfrageergebnisse gibt.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) Methode

Wählt einen einzelnen Knoten im [XPathNavigator](../) aus, indem das angegebene [XPathExpression](../../xpathexpression/)-Objekt verwendet wird.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ein [XPathExpression](../../xpathexpression/)-Objekt, das die kompilierte [XPath](../../)-Abfrage enthält. |

### Rückgabewert

Ein [XPathNavigator](../)-Objekt, das den ersten passenden Knoten für die angegebene [XPath](../../)-Abfrage enthält; andernfalls **nullptr**, wenn es keine Abfrageergebnisse gibt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XPathExpression](../../xpathexpression/)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)