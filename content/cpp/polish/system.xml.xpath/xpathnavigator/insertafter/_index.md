---
title: InsertAfter()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca obiekt XmlWriter używany do utworzenia nowego węzła siostrzanego po bieżąco wybranym węźle.
type: docs
weight: 898
url: /pl/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metoda

Zwraca obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do utworzenia nowego węzła siostrzanego po bieżąco wybranym węźle.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Wartość zwracana

Obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do utworzenia nowego węzła siostrzanego po bieżąco wybranym węźle.

## XPathNavigator::InsertAfter(String) metoda

Tworzy nowy węzeł siostrzany po bieżąco wybranym węźle przy użyciu określonego łańcucha XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Łańcuch danych XML dla nowego węzła siostrzanego. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metoda

Tworzy nowy węzeł siostrzany po bieżąco wybranym węźle przy użyciu zawartości XML obiektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Obiekt [XmlReader](../../../system.xml/xmlreader/) pozycjonowany na danych XML dla nowego węzła siostrzanego. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metoda

Tworzy nowy węzeł siostrzany po bieżąco wybranym węźle przy użyciu węzłów w określonym obiekcie [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Obiekt [XPathNavigator](../) pozycjonowany na węźle, który ma zostać dodany jako nowy węzeł siostrzany. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlWriter](../../../system.xml/xmlwriter/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)