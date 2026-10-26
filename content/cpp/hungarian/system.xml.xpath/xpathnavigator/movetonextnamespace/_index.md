---
title: MoveToNextNamespace()
second_title: Aspose.Slides for C++ API Referencia
description: Amikor felül van írva egy származtatott osztályban, a XPathNavigator-t a megadott XPathNamespaceScope-nek megfelelő következő névtércsomópontra mozgatja.
type: docs
weight: 573
url: /hu/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) módszer


Amikor felül van írva egy származtatott osztályban, a [XPathNavigator](../)-t a megadott XPathNamespaceScope-nek megfelelő következő névtércsomópontra mozgatja.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Egy XPathNamespaceScope érték, amely leírja a névtér hatókörét. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen a következő névtércsomópontra mozog; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## XPathNavigator::MoveToNextNamespace() módszer


A [XPathNavigator](../)-t a következő névtércsomópontra mozgatja.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen a következő névtércsomópontra mozog; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## Lásd még

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)