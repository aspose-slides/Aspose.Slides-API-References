---
title: MoveToNextNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, sposta l'XPathNavigator al prossimo nodo di namespace che corrisponde allo XPathNamespaceScope specificato.
type: docs
weight: 573
url: /it/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) metodo


When overridden in a derived class, moves the [XPathNavigator](../) to the next namespace node matching the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | An XPathNamespaceScope value describing the namespace scope. |

### Valore restituito

**true** if the [XPathNavigator](../) is successful moving to the next namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNextNamespace() metodo


Moves the [XPathNavigator](../) to the next namespace node.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### Valore restituito

**true** if the [XPathNavigator](../) is successful moving to the next namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Vedi anche

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)