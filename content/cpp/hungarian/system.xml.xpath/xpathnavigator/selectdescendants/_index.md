---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API referencia
description: Kiválasztja az aktuális csomópont összes olyan leszármazott csomópontját, amelyek XPathNodeType értéke egyezik.
type: docs
weight: 859
url: /hu/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) metódus

Kiválasztja az aktuális csomópont összes leszármazott csomópontját, amelyeknek egyezik az XPathNodeType értéke.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | A leszármazott csomópontok XPathNodeType értéke. |
| matchSelf | **bool** | true, ha a környezeti csomópontot is bele akarja foglalni a kiválasztásba; egyébként **false**. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/), amely a kiválasztott csomópontokat tartalmazza.

## XPathNavigator::SelectDescendants(String, String, bool) metódus

Kiválasztja az aktuális csomópont összes leszármazott csomópontját a megadott helyi név és névtér URI alapján.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | A leszármazott csomópontok helyi neve. |
| namespaceURI | [String](../../../system/string/) | A leszármazott csomópontok névtér URI-ja. |
| matchSelf | **bool** | true, ha a környezeti csomópontot is bele akarja foglalni a kiválasztásba; egyébként **false**. |

### Visszatérési érték

Egy [XPathNodeIterator](../../xpathnodeiterator/), amely a kiválasztott csomópontokat tartalmazza.

## Lásd még

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathNodeIterator](../../xpathnodeiterator/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)