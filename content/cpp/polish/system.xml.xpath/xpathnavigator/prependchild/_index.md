---
title: PrependChild()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca obiekt XmlWriter używany do tworzenia nowego węzła potomnego na początku listy węzłów potomnych bieżącego węzła.
type: docs
weight: 872
url: /pl/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() metoda

Zwraca obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do tworzenia nowego węzła potomnego na początku listy węzłów potomnych bieżącego węzła.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Wartość zwracana

Obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do tworzenia nowego węzła potomnego na początku listy węzłów potomnych bieżącego węzła.

## XPathNavigator::PrependChild(String) metoda

Tworzy nowy węzeł potomny na początku listy węzłów potomnych bieżącego węzła, używając określonego ciągu XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Ciąg danych XML dla nowego węzła potomnego. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) metoda

Tworzy nowy węzeł potomny na początku listy węzłów potomnych bieżącego węzła, używając zawartości XML określonego obiektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Obiekt [XmlReader](../../../system.xml/xmlreader/) umieszczony na danych XML dla nowego węzła potomnego. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) metoda

Tworzy nowy węzeł potomny na początku listy węzłów potomnych bieżącego węzła, używając węzłów w określonym obiekcie [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Obiekt [XPathNavigator](../) umieszczony na węźle, który ma zostać dodany jako nowy węzeł potomny. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlWriter](../../../system.xml/xmlwriter/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)