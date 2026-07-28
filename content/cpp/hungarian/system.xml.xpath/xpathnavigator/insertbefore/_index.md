---
title: InsertBefore()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy XmlWriter objektumot, amelyet új testvércsomópont létrehozására használhat a jelenleg kiválasztott csomópont előtt.
type: docs
weight: 911
url: /hu/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() metódus

Visszaad egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet új testvércsomópont létrehozására használhat a jelenleg kiválasztott csomópont előtt.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Visszatérési érték

Egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet új testvércsomópont létrehozására használhat a jelenleg kiválasztott csomópont előtt.

## XPathNavigator::InsertBefore(String) metódus

Új testvércsomópontot hoz létre a jelenleg kiválasztott csomópont előtt a megadott XML karakterlánc használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Az új testvércsomópont XML adatkarakterlánca. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) metódus

Új testvércsomópontot hoz létre a jelenleg kiválasztott csomópont előtt a megadott [XmlReader](../../../system.xml/xmlreader/) objektum XML tartalmának használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely az új testvércsomópont XML adatainak helyén van. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) metódus

Új testvércsomópontot hoz létre a jelenleg kiválasztott csomópont előtt a megadott [XPathNavigator](../) csomópontjainak használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Egy [XPathNavigator](../) objektum, amely arra a csomópontra mutat, amelyet új testvércsomópontként ad hozzá. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlWriter](../../../system.xml/xmlwriter/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Névtere [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)