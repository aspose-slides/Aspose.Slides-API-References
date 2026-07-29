---
title: MoveToFirstNamespace()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass, flyttar den XPathNavigator till den första namnrymdsnoden som matchar den angivna XPathNamespaceScope.
type: docs
weight: 560
url: /sv/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) metod


När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](../) till den första namnrymdsnoden som matchar den angivna XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Ett XPathNamespaceScope-värde som beskriver namnrymdens omfattning. |

### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till den första namnrymdsnoden; annars **false**. Om **false**, förblir positionen för [XPathNavigator](../) oförändrad.

## XPathNavigator::MoveToFirstNamespace() metod


Flyttar [XPathNavigator](../) till den första namnrymdsnoden för den aktuella noden.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```


### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till den första namnrymdsnoden; annars **false**. Om **false**, förblir positionen för [XPathNavigator](../) oförändrad.

## Se även

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)