---
title: Matches()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy az aktuális csomópont egyezik-e a megadott XPathExpression-nel.
type: docs
weight: 820
url: /hu/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) metódus


Meghatározza, hogy az aktuális csomópont egyezik-e a megadott [XPathExpression](../../xpathexpression/)-val.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Egy [XPathExpression](../../xpathexpression/) objektum, amely a lefordított [XPath](../../) kifejezést tartalmazza. |

### Visszatérési érték

**true** ha az aktuális csomópont egyezik a [XPathExpression](../../xpathexpression/)-val; egyébként **false**.

## XPathNavigator::Matches(String) metódus


Meghatározza, hogy az aktuális csomópont egyezik-e a megadott [XPath](../../) kifejezéssel.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [XPath](../../) kifejezés. |

### Visszatérési érték

**true** ha az aktuális csomópont egyezik a megadott [XPath](../../) kifejezéssel; egyébként **false**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathExpression](../../xpathexpression/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)