---
title: Evaluate()
second_title: Aspose.Slides C++ API-referencia
description: Kiértékeli a megadott XPath kifejezést, és visszaadja a típusos eredményt.
type: docs
weight: 807
url: /hu/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) metódus


Kiértékeli a megadott [XPath](../../) kifejezést, és visszaadja a típusos eredményt.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Egy karakterlánc, amely egy [XPath](../../) kifejezést ábrázol, és kiértékelhető. |

### Visszatérési érték

A kifejezés eredménye ([Boolean](../../../system/boolean/), szám, karakterlánc vagy csomópontkészlet). Ez megfelel a [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) vagy [XPathNodeIterator](../../xpathnodeiterator/) objektumoknak, sorrendben.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) metódus


Kiértékeli a megadott [XPath](../../) kifejezést, és visszaadja a típusos eredményt, a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum használatával, amely a [XPath](../../) kifejezés névtér-előtagjait oldja fel.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Egy karakterlánc, amely egy [XPath](../../) kifejezést ábrázol, és kiértékelhető. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | A [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a [XPath](../../) kifejezés névtér-előtagjait oldja fel. |

### Visszatérési érték

A kifejezés eredménye ([Boolean](../../../system/boolean/), szám, karakterlánc vagy csomópontkészlet). Ez megfelel a [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) vagy [XPathNodeIterator](../../xpathnodeiterator/) objektumoknak, sorrendben.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) metódus


Kiértékeli a [XPathExpression](../../xpathexpression/) kifejezést, és visszaadja a típusos eredményt.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Egy [XPathExpression](../../xpathexpression/), amely kiértékelhető. |

### Visszatérési érték

A kifejezés eredménye ([Boolean](../../../system/boolean/), szám, karakterlánc vagy csomópontkészlet). Ez megfelel a [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) vagy [XPathNodeIterator](../../xpathnodeiterator/) objektumoknak, sorrendben.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) metódus


A megadott kontextust használja a [XPathExpression](../../xpathexpression/) kiértékelésére, és visszaadja a típusos eredményt.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Egy [XPathExpression](../../xpathexpression/), amely kiértékelhető. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Egy [XPathNodeIterator](../../xpathnodeiterator/), amely azokra a kiválasztott csomópontkészletekre mutat, amelyeken a kiértékelés végrehajtandó. |

### Visszatérési érték

A kifejezés eredménye ([Boolean](../../../system/boolean/), szám, karakterlánc vagy csomópontkészlet). Ez megfelel a [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) vagy [XPathNodeIterator](../../xpathnodeiterator/) objektumoknak, sorrendben.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Osztály [XPathExpression](../../xpathexpression/)
* Osztály [XPathNodeIterator](../../xpathnodeiterator/)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)