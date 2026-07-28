---
title: AppendChild()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Zwraca obiekt XmlWriter używany do tworzenia jednego lub więcej nowych węzłów potomnych na końcu listy węzłów potomnych bieżącego węzła.
type: docs
weight: 885
url: /pl/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metoda

Zwraca obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do tworzenia jednego lub więcej nowych węzłów potomnych na końcu listy węzłów potomnych bieżącego węzła.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Wartość zwracana

Obiekt [XmlWriter](../../../system.xml/xmlwriter/) używany do tworzenia nowych węzłów potomnych na końcu listy węzłów potomnych bieżącego węzła.

## XPathNavigator::AppendChild(String) metoda

Tworzy nowy węzeł potomny na końcu listy węzłów potomnych bieżącego węzła przy użyciu określonego łańcucha danych XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Łańcuch danych XML dla nowego węzła potomnego. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metoda

Tworzy nowy węzeł potomny na końcu listy węzłów potomnych bieżącego węzła przy użyciu zawartości XML obiektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Obiekt [XmlReader](../../../system.xml/xmlreader/) umieszczony na danych XML dla nowego węzła potomnego. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metoda

Tworzy nowy węzeł potomny na końcu listy węzłów potomnych bieżącego węzła przy użyciu węzłów w [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Obiekt [XPathNavigator](../) umieszczony na węźle, który ma zostać dodany jako nowy węzeł potomny. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlWriter](../../../system.xml/xmlwriter/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)