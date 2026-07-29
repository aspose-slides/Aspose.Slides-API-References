---
title: PrependChild()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett XmlWriter-objekt som används för att skapa en ny undernod i början av listan med undernoder för den aktuella noden.
type: docs
weight: 872
url: /sv/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() method

Returnerar ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa en ny undernod i början av listan med undernoder för den aktuella noden.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Returvärde

Ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa en ny undernod i början av listan med undernoder för den aktuella noden.

## XPathNavigator::PrependChild(String) method

Skapar en ny undernod i början av listan med undernoder för den aktuella noden med den specificerade XML-strängen.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | XML-datatsträngen för den nya undernoden. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) method

Skapar en ny undernod i början av listan med undernoder för den aktuella noden med XML-innehållet i det specificerade [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt placerat på XML-data för den nya undernoden. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) method

Skapar en ny undernod i början av listan med undernoder för den aktuella noden med noderna i det specificerade [XPathNavigator](../)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ett [XPathNavigator](../)-objekt placerat på noden som ska läggas till som den nya undernoden. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlWriter](../../../system.xml/xmlwriter/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)