---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API dokumentáció
description: Kiválasztja az aktuális csomópont összes olyan ős csomópontját, amelyek egyező XPathNodeType értékkel rendelkeznek.
type: docs
weight: 846
url: /hu/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metódus


Kiválasztja az aktuális csomópont összes ős csomópontját, amelyek megfelelnek a megadott XPathNodeType értéknek.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Az ős csomópontok XPathNodeType-ja. |
| matchSelf | **bool** | A kontextuscsomópont beillesztéséhez a kiválasztásba, **true**; egyébként **false**. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/) ami a kiválasztott csomópontokat tartalmazza. A visszaadott csomópontok fordított dokumentumsorrendben vannak.

## XPathNavigator::SelectAncestors(String, String, bool) metódus


Kiválasztja az aktuális csomópont összes ős csomópontját, amelyek a megadott helyi névvel és névtér-URI-val rendelkeznek.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az ős csomópontok helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az ős csomópontok névtér-URI-ja. |
| matchSelf | **bool** | A kontextuscsomópont beillesztéséhez a kiválasztásba, **true**; egyébként **false**. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/) ami a kiválasztott csomópontokat tartalmazza. A visszaadott csomópontok fordított dokumentumsorrendben vannak.

## Lásd még

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathNodeIterator](../../xpathnodeiterator/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)