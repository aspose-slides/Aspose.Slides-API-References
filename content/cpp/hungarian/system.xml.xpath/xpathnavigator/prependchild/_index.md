---
title: PrependChild()
second_title: Aspose.Slides C++ API-referenciája
description: Visszaad egy XmlWriter objektumot, amelyet az aktuális csomópont gyermekcsomópontjainak listájának elején új gyermekcsomópont létrehozásához használnak.
type: docs
weight: 872
url: /hu/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() metódus

Visszaad egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet egy új gyermekcsomópont létrehozására használnak a jelenlegi csomópont gyermekcsomópontjainak listájának elején.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Visszatérési érték

Egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet egy új gyermekcsomópont létrehozására használnak a jelenlegi csomópont gyermekcsomópontjainak listájának elején.

## XPathNavigator::PrependChild(String) metódus

Új gyermekcsomópontot hoz létre a jelenlegi csomópont gyermekcsomópontjainak listájának elején a megadott XML-karakterlánc használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Az új gyermekcsomópont XML adatkarakterlánca. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) metódus

Új gyermekcsomópontot hoz létre a jelenlegi csomópont gyermekcsomópontjainak listájának elején a megadott [XmlReader](../../../system.xml/xmlreader/) objektum XML tartalmának használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely az új gyermekcsomópont XML adatára mutat. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) metódus

Új gyermekcsomópontot hoz létre a jelenlegi csomópont gyermekcsomópontjainak listájának elején a megadott [XPathNavigator](../) objektumban található csomópontok használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Egy [XPathNavigator](../) objektum, amely a hozzáadandó új gyermekcsomópontra mutat. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlWriter](../../../system.xml/xmlwriter/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Névtere [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)