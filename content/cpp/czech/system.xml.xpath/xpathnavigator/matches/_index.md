---
title: Matches()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda aktuální uzel odpovídá zadanému XPathExpression.
type: docs
weight: 820
url: /cs/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) metoda


Určuje, zda aktuální uzel odpovídá zadanému [XPathExpression](../../xpathexpression/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Objekt [XPathExpression](../../xpathexpression/) obsahující zkompilovaný výraz [XPath](../../). |

### Návratová hodnota

**true** pokud aktuální uzel odpovídá [XPathExpression](../../xpathexpression/); jinak **false**.

## XPathNavigator::Matches(String) metoda


Určuje, zda aktuální uzel odpovídá zadanému výrazu [XPath](../../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) výraz. |

### Návratová hodnota

**true** pokud aktuální uzel odpovídá zadanému výrazu [XPath](../../); jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathExpression](../../xpathexpression/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)