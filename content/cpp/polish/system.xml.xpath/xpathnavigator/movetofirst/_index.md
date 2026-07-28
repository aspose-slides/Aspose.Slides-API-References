---
title: MoveToFirst()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Przenosi XPathNavigator do pierwszego węzła rodzeństwa bieżącego węzła.
type: docs
weight: 612
url: /pl/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() metoda

Przenosi [XPathNavigator](../) do pierwszego węzła rodzeństwa bieżącego węzła.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się pomyślnie, przenosząc do pierwszego węzła rodzeństwa bieżącego węzła; **false** jeśli nie ma pierwszego rodzeństwa, lub jeśli [XPathNavigator](../) jest aktualnie ustawiony na węzeł atrybutu. Jeśli [XPathNavigator](../) jest już ustawiony na pierwszym rodzeństwie, [XPathNavigator](../) zwróci **true** i nie zmieni swojej pozycji. Jeśli [XPathNavigator::MoveToFirst](./) zwróci **false**, ponieważ nie ma pierwszego rodzeństwa, lub jeśli [XPathNavigator](../) jest aktualnie ustawiony na atrybucie, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## Zobacz także

* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)