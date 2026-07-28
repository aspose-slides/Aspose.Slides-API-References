---
title: Matches()
second_title: Aspose.Slides dla C++ Referencja API
description: Określa, czy bieżący węzeł pasuje do określonego XPathExpression.
type: docs
weight: 820
url: /pl/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) metoda

Określa, czy bieżący węzeł pasuje do określonego [XPathExpression](../../xpathexpression/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Obiekt [XPathExpression](../../xpathexpression/) zawierający skompilowane wyrażenie [XPath](../../). |

### Wartość zwracana

**true** jeżeli bieżący węzeł pasuje do [XPathExpression](../../xpathexpression/); w przeciwnym razie **false**.

## XPathNavigator::Matches(String) metoda

Określa, czy bieżący węzeł pasuje do określonego [XPath](../../) wyrażenia.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Wyrażenie [XPath](../../). |

### Wartość zwracana

**true** jeżeli bieżący węzeł pasuje do określonego wyrażenia [XPath](../../); w przeciwnym razie **false**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathExpression](../../xpathexpression/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)