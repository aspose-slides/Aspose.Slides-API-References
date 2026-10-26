---
title: InsertAfter()
second_title: Aspose.Slides C++ API-referencia
description: Visszaad egy XmlWriter objektumot, amelyet az aktuálisan kiválasztott csomópont után új testvércsomópont létrehozásához használnak.
type: docs
weight: 898
url: /hu/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metódus

Visszaad egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet az aktuálisan kiválasztott csomópont után új testvércsomópont létrehozásához használnak.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Visszatérési érték

Egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet az aktuálisan kiválasztott csomópont után új testvércsomópont létrehozásához használnak.

## XPathNavigator::InsertAfter(String) metódus

Új testvércsomópontot hoz létre az aktuálisan kiválasztott csomópont után a megadott XML karakterlánc használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Az új testvércsomópont XML adatkarakterlánca. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metódus

Új testvércsomópontot hoz létre az aktuálisan kiválasztott csomópont után a megadott [XmlReader](../../../system.xml/xmlreader/) objektum XML tartalmának felhasználásával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely az új testvércsomópont XML adatára van pozícionálva. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metódus

Új testvércsomópontot hoz létre az aktuálisan kiválasztott csomópont után a megadott [XPathNavigator](../) objektum csomópontjainak felhasználásával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Egy [XPathNavigator](../) objektum, amely a hozzáadandó új testvércsomópont csomópontjára van pozícionálva. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlWriter](../../../system.xml/xmlwriter/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Névtér [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)