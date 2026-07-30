---
title: MoveToFirstNamespace()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Když je přepsáno v odvozené třídě, přesune XPathNavigator na první uzel jmenného prostoru, který odpovídá zadanému XPathNamespaceScope.
type: docs
weight: 560
url: /cs/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) metoda


Když je přepsáno v odvozené třídě, přesune [XPathNavigator](../) na první uzel jmenného prostoru, který odpovídá zadanému XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Hodnota XPathNamespaceScope popisující rozsah jmenného prostoru. |

### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšné při přesunu na první uzel jmenného prostoru; jinak **false**. Pokud **false**, pozice [XPathNavigator](../) zůstává nezměněna.

## XPathNavigator::MoveToFirstNamespace() metoda


Přesune [XPathNavigator](../) na první uzel jmenného prostoru aktuálního uzlu.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```


### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšné při přesunu na první uzel jmenného prostoru; jinak **false**. Pokud **false**, pozice [XPathNavigator](../) zůstává nezměněna.

## Viz také

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* třída [XPathNavigator](../)
* jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)