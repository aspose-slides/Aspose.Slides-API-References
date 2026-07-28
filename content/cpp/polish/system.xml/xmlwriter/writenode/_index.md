---
title: WriteNode()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Gdy zostanie przesłonięta w klasie pochodnej, kopiuje wszystko z odczytywacza do zapisu i przenosi odczytywacz na początek następnego elementu podrzędnego.
type: docs
weight: 430
url: /pl/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) metoda

Gdy zostanie przesłonięta w klasie pochodnej, kopiuje wszystko z odczytywacza do zapisu i przenosi odczytywacz na początek następnego elementu podrzędnego.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Obiekt [XmlReader](../../xmlreader/) do odczytu. |
| defattr | **bool** | **true**, aby skopiować domyślne atrybuty z [XmlReader](../../xmlreader/); w przeciwnym razie **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) metoda

Kopiuje wszystko z obiektu XPathNavigator do zapisu. Pozycja XPathNavigator pozostaje niezmieniona.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Obiekt XPathNavigator do skopiowania. |
| defattr | **bool** | **true**, aby skopiować domyślne atrybuty; w przeciwnym razie **false**. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlReader](../../xmlreader/)
* Klasa [XmlWriter](../)
* Klasa [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)