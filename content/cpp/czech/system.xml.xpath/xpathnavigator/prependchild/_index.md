---
title: PrependChild()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací objekt XmlWriter použitý k vytvoření nového poduzlu na začátku seznamu poduzlů aktuálního uzlu.
type: docs
weight: 872
url: /cs/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() metoda

Vrací objekt [XmlWriter](../../../system.xml/xmlwriter/) použitý k vytvoření nového poduzlu na začátku seznamu poduzlů aktuálního uzlu.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Návratová hodnota

Objekt [XmlWriter](../../../system.xml/xmlwriter/) použitý k vytvoření nového poduzlu na začátku seznamu poduzlů aktuálního uzlu.

## XPathNavigator::PrependChild(String) metoda

Vytvoří nový poduzel na začátku seznamu poduzlů aktuálního uzlu pomocí zadaného řetězce XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Řetězec XML dat pro nový poduzel. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) metoda

Vytvoří nový poduzel na začátku seznamu poduzlů aktuálního uzlu pomocí obsahu XML objektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Objekt [XmlReader](../../../system.xml/xmlreader/) umístěný na XML datech pro nový poduzel. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) metoda

Vytvoří nový poduzel na začátku seznamu poduzlů aktuálního uzlu pomocí uzlů v objektu [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objekt [XPathNavigator](../) umístěný na uzlu, který se má přidat jako nový poduzel. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlWriter](../../../system.xml/xmlwriter/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)