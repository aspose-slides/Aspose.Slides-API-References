---
title: AppendChild()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací objekt XmlWriter používaný k vytvoření jednoho nebo více nových uzlů potomka na konci seznamu uzlů potomka aktuálního uzlu.
type: docs
weight: 885
url: /cs/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metoda

Vrací objekt [XmlWriter](../../../system.xml/xmlwriter/) používaný k vytvoření jednoho nebo více nových uzlů potomka na konci seznamu uzlů potomka aktuálního uzlu.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Návratová hodnota

Objekt [XmlWriter](../../../system.xml/xmlwriter/) používaný k vytvoření nových uzlů potomka na konci seznamu uzlů potomka aktuálního uzlu.

## XPathNavigator::AppendChild(String) metoda

Vytváří nový uzel potomka na konci seznamu uzlů potomka aktuálního uzlu pomocí zadaného řetězce XML dat.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Řetězec XML dat pro nový uzel potomka. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metoda

Vytváří nový uzel potomka na konci seznamu uzlů potomka aktuálního uzlu pomocí obsahu XML objektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Objekt [XmlReader](../../../system.xml/xmlreader/) umístěný na XML data pro nový uzel potomka. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metoda

Vytváří nový uzel potomka na konci seznamu uzlů potomka aktuálního uzlu pomocí uzlů ve specifikovaném [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objekt [XPathNavigator](../) umístěný na uzlu, který má být přidán jako nový uzel potomka. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlWriter](../../../system.xml/xmlwriter/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)