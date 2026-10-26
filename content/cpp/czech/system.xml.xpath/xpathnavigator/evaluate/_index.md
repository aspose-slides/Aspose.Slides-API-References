---
title: Evaluate()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vyhodnotí zadaný výraz XPath a vrátí typovaný výsledek.
type: docs
weight: 807
url: /cs/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) metoda


Vyhodnotí zadaný [XPath](../../) výraz a vrátí typovaný výsledek.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Řetězec představující [XPath](../../) výraz, který lze vyhodnotit. |

### Návratová hodnota

Výsledek výrazu ([Boolean](../../../system/boolean/), číslo, řetězec nebo množina uzlů). Toto odpovídá objektům [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) nebo [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) metoda


Vyhodnotí zadaný [XPath](../../) výraz a vrátí typovaný výsledek pomocí objektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), který je určen k rozluštění předpon jmenných prostorů ve výrazu [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Řetězec představující [XPath](../../) výraz, který lze vyhodnotit. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozluštění předpon jmenných prostorů ve výrazu [XPath](../../). |

### Návratová hodnota

Výsledek výrazu ([Boolean](../../../system/boolean/), číslo, řetězec nebo množina uzlů). Toto odpovídá objektům [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) nebo [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) metoda


Vyhodnotí [XPathExpression](../../xpathexpression/) a vrátí typovaný výsledek.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Objekt [XPathExpression](../../xpathexpression/), který lze vyhodnotit. |

### Návratová hodnota

Výsledek výrazu ([Boolean](../../../system/boolean/), číslo, řetězec nebo množina uzlů). Toto odpovídá objektům [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) nebo [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) metoda


Použije dodaný kontext k vyhodnocení [XPathExpression](../../xpathexpression/) a vrátí typovaný výsledek.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Objekt [XPathExpression](../../xpathexpression/), který lze vyhodnotit. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Objekt [XPathNodeIterator](../../xpathnodeiterator/), který ukazuje na vybranou množinu uzlů, nad kterou se má provést vyhodnocení. |

### Návratová hodnota

Výsledek výrazu ([Boolean](../../../system/boolean/), číslo, řetězec nebo množina uzlů). Toto odpovídá objektům [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) nebo [XPathNodeIterator](../../xpathnodeiterator/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XPathExpression](../../xpathexpression/)
* Třída [XPathNodeIterator](../../xpathnodeiterator/)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)