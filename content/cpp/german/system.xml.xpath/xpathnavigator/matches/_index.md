---
title: Matches()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der aktuelle Knoten dem angegebenen XPathExpression entspricht.
type: docs
weight: 820
url: /de/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) Methode


Bestimmt, ob der aktuelle Knoten dem angegebenen [XPathExpression](../../xpathexpression/) entspricht.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ein [XPathExpression](../../xpathexpression/)-Objekt, das den kompilierten [XPath](../../)-Ausdruck enthält. |

### Rückgabewert

**true** wenn der aktuelle Knoten dem [XPathExpression](../../xpathexpression/) entspricht; andernfalls **false**.

## XPathNavigator::Matches(String) Methode


Bestimmt, ob der aktuelle Knoten dem angegebenen [XPath](../../)-Ausdruck entspricht.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Der [XPath](../../)-Ausdruck. |

### Rückgabewert

**true** wenn der aktuelle Knoten dem angegebenen [XPath](../../)-Ausdruck entspricht; andernfalls **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathExpression](../../xpathexpression/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)