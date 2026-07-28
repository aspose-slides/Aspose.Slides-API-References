---
title: Select()
second_title: Aspose.Slides dla C++ Referencja API
description: Wybiera zestaw węzłów, używając określonego wyrażenia XPath.
type: docs
weight: 794
url: /pl/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) metoda

Wybiera zestaw węzłów, używając określonego wyrażenia [XPath](../../).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Obiekt [String](../../../system/string/) reprezentujący wyrażenie [XPath](../../). |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) wskazujący na wybrany zestaw węzłów.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) metoda

Wybiera zestaw węzłów przy użyciu określonego wyrażenia [XPath](../../) oraz obiektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) przeznaczonego do rozwiązywania prefiksów przestrzeni nazw.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Obiekt [String](../../../system/string/) reprezentujący wyrażenie [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania prefiksów przestrzeni nazw. |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) wskazujący na wybrany zestaw węzłów.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) metoda

Wybiera zestaw węzłów przy użyciu określonego [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Obiekt [XPathExpression](../../xpathexpression/) zawierający skompilowane zapytanie [XPath](../../). |

### Wartość zwracana

Obiekt [XPathNodeIterator](../../xpathnodeiterator/) wskazujący na wybrany zestaw węzłów.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNodeIterator](../../xpathnodeiterator/)
* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XPathExpression](../../xpathexpression/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)