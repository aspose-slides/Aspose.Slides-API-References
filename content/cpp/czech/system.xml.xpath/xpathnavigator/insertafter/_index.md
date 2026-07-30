---
title: InsertAfter()
second_title: Aspose.Slides pro C++ - API Reference
description: Vrátí objekt XmlWriter používaný k vytvoření nového sourozeneckého uzlu po aktuálně vybraném uzlu.
type: docs
weight: 898
url: /cs/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metoda


Vrátí objekt [XmlWriter](../../../system.xml/xmlwriter/) používaný k vytvoření nového sourozeneckého uzlu po aktuálně vybraném uzlu.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### Návratová hodnota

Objekt [XmlWriter](../../../system.xml/xmlwriter/) používáný k vytvoření nového sourozeneckého uzlu po aktuálně vybraném uzlu.

## XPathNavigator::InsertAfter(String) metoda


Vytvoří nový sourozenecký uzel po aktuálně vybraném uzlu pomocí zadaného řetězce XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Řetězec XML dat pro nový sourozenecký uzel. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metoda


Vytvoří nový sourozenecký uzel po aktuálně vybraném uzlu pomocí obsahu XML objektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Objekt [XmlReader](../../../system.xml/xmlreader/) umístěný na XML datech pro nový sourozenecký uzel. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metoda


Vytvoří nový sourozenecký uzel po aktuálně vybraném uzlu pomocí uzlů v objektu [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objekt [XPathNavigator](../) umístěný na uzlu, který se má přidat jako nový sourozenecký uzel. |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [XmlWriter](../../../system.xml/xmlwriter/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)