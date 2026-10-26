---
title: MoveToFirstNamespace()
second_title: Aspose.Slides for C++ API Referenciája
description: Ha egy származtatott osztályban felül van definiálva, a XPathNavigator az első olyan névtércsomópontra kerül, amely megfelel a megadott XPathNamespaceScope.
type: docs
weight: 560
url: /hu/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) metódus


Amikor egy származtatott osztályban felül van definiálva, a [XPathNavigator](../)-t az első olyan névtércsomópontra mozgatja, amely megfelel a megadott XPathNamespaceScope-nak.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Egy XPathNamespaceScope érték, amely leírja a névtér hatókörét. |

### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen az első névtércsomópontra mozog; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## XPathNavigator::MoveToFirstNamespace() metódus


A [XPathNavigator](../)-t az aktuális csomóponthoz tartozó első névtércsomópontra mozgatja.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```


### Visszatérési érték

**true** ha a [XPathNavigator](../) sikeresen az első névtércsomópontra mozog; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## Lásd még

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)