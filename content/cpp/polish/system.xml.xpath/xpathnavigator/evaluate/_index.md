---
title: Evaluate()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Ocena określonego wyrażenia XPath i zwraca typowy wynik.
type: docs
weight: 807
url: /pl/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) metoda

Ocena określonego [XPath](../../) wyrażenia i zwraca typowy wynik.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ciąg znaków reprezentujący wyrażenie [XPath](../../) , które może zostać ocenione. |

### Wartość zwracana

Wynik wyrażenia ([Boolean](../../../system/boolean/), liczba, ciąg znaków lub zestaw węzłów). Odwzorowuje się to na obiekty [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) lub [XPathNodeIterator](../../xpathnodeiterator/) odpowiednio.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) metoda

Ocena określonego [XPath](../../) wyrażenia i zwraca typowy wynik, używając obiektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) do rozwiązywania prefiksów przestrzeni nazw w wyrażeniu [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ciąg znaków reprezentujący wyrażenie [XPath](../../) , które może zostać ocenione. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania prefiksów przestrzeni nazw w wyrażeniu [XPath](../../). |

### Wartość zwracana

Wynik wyrażenia ([Boolean](../../../system/boolean/), liczba, ciąg znaków lub zestaw węzłów). Odwzorowuje się to na obiekty [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) lub [XPathNodeIterator](../../xpathnodeiterator/) odpowiednio.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) metoda

Ocena [XPathExpression](../../xpathexpression/) i zwraca typowy wynik.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) , które może zostać ocenione. |

### Wartość zwracana

Wynik wyrażenia ([Boolean](../../../system/boolean/), liczba, ciąg znaków lub zestaw węzłów). Odwzorowuje się to na obiekty [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) lub [XPathNodeIterator](../../xpathnodeiterator/) odpowiednio.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) metoda

Używa dostarczonego kontekstu do oceny [XPathExpression](../../xpathexpression/) i zwraca typowy wynik.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) , które może zostać ocenione. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | [XPathNodeIterator](../../xpathnodeiterator/) wskazujący na wybrany zestaw węzłów, na którym ma zostać wykonana ocena. |

### Wartość zwracana

Wynik wyrażenia ([Boolean](../../../system/boolean/), liczba, ciąg znaków lub zestaw węzłów). Odwzorowuje się to na obiekty [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) lub [XPathNodeIterator](../../xpathnodeiterator/) odpowiednio.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XPathExpression](../../xpathexpression/)
* Klasa [XPathNodeIterator](../../xpathnodeiterator/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)