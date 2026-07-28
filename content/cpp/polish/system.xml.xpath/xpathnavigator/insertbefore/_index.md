---
title: InsertBefore()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca obiekt XmlWriter używany do utworzenia nowego węzła rodzeństwa przed aktualnie wybranym węzłem.
type: docs
weight: 911
url: /pl/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() metoda

Zwraca obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do utworzenia nowego węzła rodzeństwa przed aktualnie wybranym węzłem.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Wartość zwracana

Obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do utworzenia nowego węzła rodzeństwa przed aktualnie wybranym węzłem.

## XPathNavigator::InsertBefore(String) metoda

Tworzy nowy węzeł rodzeństwa przed aktualnie wybranym węzłem przy użyciu określonego ciągu XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Ciąg danych XML dla nowego węzła rodzeństwa. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) metoda

Tworzy nowy węzeł rodzeństwa przed aktualnie wybranym węzłem przy użyciu zawartości XML określonego obiektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Obiekt [XmlReader](../../../system.xml/xmlreader/) znajdujący się na danych XML nowego węzła rodzeństwa. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) metoda

Tworzy nowy węzeł rodzeństwa przed aktualnie wybranym węzłem przy użyciu węzłów w określonym [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Obiekt [XPathNavigator](../) znajdujący się na węźle, który ma zostać dodany jako nowy węzeł rodzeństwa. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlWriter](../../../system.xml/xmlwriter/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)