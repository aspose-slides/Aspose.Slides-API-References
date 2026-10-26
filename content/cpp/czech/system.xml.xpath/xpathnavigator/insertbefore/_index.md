---
title: InsertBefore()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací objekt XmlWriter použitý k vytvoření nového sourozeneckého uzlu před aktuálně vybraným uzlem.
type: docs
weight: 911
url: /cs/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() metoda

Vrací objekt [XmlWriter](../../../system.xml/xmlwriter/) použitý k vytvoření nového sourozeneckého uzlu před aktuálně vybraným uzlem.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Návratová hodnota

Objekt [XmlWriter](../../../system.xml/xmlwriter/) použitý k vytvoření nového sourozeneckého uzlu před aktuálně vybraným uzlem.

## XPathNavigator::InsertBefore(String) metoda

Vytvoří nový sourozenecký uzel před aktuálně vybraným uzlem pomocí zadaného řetězce XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Řetězec XML dat pro nový sourozenecký uzel. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) metoda

Vytvoří nový sourozenecký uzel před aktuálně vybraným uzlem pomocí XML obsahu zadaného objektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Objekt [XmlReader](../../../system.xml/xmlreader/) umístěný na XML datech pro nový sourozenecký uzel. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) metoda

Vytvoří nový sourozenecký uzel před aktuálně vybraným uzlem pomocí uzlů ve zvoleném [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objekt [XPathNavigator](../) umístěný na uzlu, který má být přidán jako nový sourozenecký uzel. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)