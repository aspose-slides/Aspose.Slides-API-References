---
title: AppendChild()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaad egy XmlWriter objektumot, amelyet a jelenlegi csomópont gyermekcsomópontjainak listájának végén egy vagy több új gyermekcsomópont létrehozására használnak.
type: docs
weight: 885
url: /hu/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metódus


Visszaad egy [XmlWriter](../../../system.xml/xmlwriter/) objektumot, amelyet a jelenlegi csomópont gyermekcsomópontjainak listájának végén egy vagy több új gyermekcsomópont létrehozására használnak.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### Visszatérési érték

Egy [XmlWriter](../../../system.xml/xmlwriter/) objektum, amelyet a jelenlegi csomópont gyermekcsomópontjainak listájának végén új gyermekcsomópontok létrehozására használnak.

## XPathNavigator::AppendChild(String) metódus


Létrehoz egy új gyermekcsomópontot a jelenlegi csomópont gyermekcsomópontjainak listájának végén a megadott XML adatkarakterlánc használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Az új gyermekcsomópont XML adatkarakterlánca. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metódus


Létrehoz egy új gyermekcsomópontot a jelenlegi csomópont gyermekcsomópontjainak listájának végén a megadott [XmlReader](../../../system.xml/xmlreader/) objektum XML tartalmának használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely az új gyermekcsomópont XML adataira mutat. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metódus


Létrehoz egy új gyermekcsomópontot a jelenlegi csomópont gyermekcsomópontjainak listájának végén a megadott [XPathNavigator](../) objektumban található csomópontok használatával.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Egy [XPathNavigator](../) objektum, amely arra a csomópontra mutat, amelyet új gyermekcsomópontként ad hozzá. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlWriter](../../../system.xml/xmlwriter/)
* Osztály [XPathNavigator](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)