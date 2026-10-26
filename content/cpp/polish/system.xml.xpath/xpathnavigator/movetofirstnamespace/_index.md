---
title: MoveToFirstNamespace()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, przenosi XPathNavigator do pierwszego węzła przestrzeni nazw, który pasuje do określonego XPathNamespaceScope.
type: docs
weight: 560
url: /pl/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) metoda

Gdy zostanie przesłonięta w klasie pochodnej, przenosi [XPathNavigator](../) do pierwszego węzła przestrzeni nazw, który pasuje do określonego XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Wartość XPathNamespaceScope opisująca zakres przestrzeni nazw. |

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się powodzeniem przy przenoszeniu do pierwszego węzła przestrzeni nazw; w przeciwnym razie **false**. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## XPathNavigator::MoveToFirstNamespace() metoda

Przenosi [XPathNavigator](../) do pierwszego węzła przestrzeni nazw bieżącego węzła.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Wartość zwracana

**true** jeśli [XPathNavigator](../) zakończy się powodzeniem przy przenoszeniu do pierwszego węzła przestrzeni nazw; w przeciwnym razie **false**. Jeśli **false**, pozycja [XPathNavigator](../) pozostaje niezmieniona.

## Zobacz także

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)