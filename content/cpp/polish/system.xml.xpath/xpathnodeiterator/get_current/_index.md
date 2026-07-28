---
title: get_Current()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, zwraca obiekt XPathNavigator dla tego XPathNodeIterator, umieszczony na bieżącym węźle kontekstowym.
type: docs
weight: 1
url: /pl/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metoda


Gdy zostanie przesłonięta w klasie pochodnej, zwraca obiekt [XPathNavigator](../../xpathnavigator/) dla tego [XPathNodeIterator](../), umieszczony na bieżącym węźle kontekstowym.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### Wartość zwracana

Obiekt [XPathNavigator](../../xpathnavigator/) umieszczony na węźle kontekstowym, z którego wybrano zbiór węzłów. Metodę [XPathNodeIterator::MoveNext](../movenext/) należy wywołać, aby przenieść [XPathNodeIterator](../) do pierwszego węzła w wybranym zbiorze.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNavigator](../../xpathnavigator/)
* Klasa [XPathNodeIterator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)