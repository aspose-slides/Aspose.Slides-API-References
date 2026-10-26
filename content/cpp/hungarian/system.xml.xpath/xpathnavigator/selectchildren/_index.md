---
title: SelectChildren()
second_title: Aspose.Slides C++ API referenciája
description: Kiválasztja az aktuális csomópont összes olyan gyermekcsomópontját, amelynek megegyező a XPathNodeType értéke.
type: docs
weight: 833
url: /hu/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) metódus


Kiválasztja az aktuális csomópont összes olyan gyermekcsomópontját, amelynek megegyező a XPathNodeType értéke.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | A gyermekcsomópontok XPathNodeType értéke. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/) amely a kiválasztott csomópontokat tartalmazza.

## XPathNavigator::SelectChildren(String, String) metódus


Kiválasztja az aktuális csomópont összes olyan gyermekcsomópontját, amelynek a megadott helyi neve és névtér-URI-ja van.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A gyermekcsomópontok helyi neve. |
| namespaceURI | [String](../../../system/string/) | A gyermekcsomópontok névtér-URI-ja. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/) amely a kiválasztott csomópontokat tartalmazza.

## Lásd még

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)