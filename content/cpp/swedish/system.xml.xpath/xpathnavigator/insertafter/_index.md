---
title: InsertAfter()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett XmlWriter-objekt som används för att skapa en ny syskonnod efter den för närvarande markerade noden.
type: docs
weight: 898
url: /sv/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metod


Returnerar ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod efter den för närvarande markerade noden.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### Returvärde

Ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod efter den för närvarande markerade noden.

## XPathNavigator::InsertAfter(String) metod


Skapar en ny syskonnod efter den för närvarande markerade noden med den angivna XML-strängen.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | XML-datasträngen för den nya syskonnoden. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metod


Skapar en ny syskonnod efter den för närvarande markerade noden med XML-innehållet i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som är placerat på XML-datan för den nya syskonnoden. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metod


Skapar en ny syskonnod efter den för närvarande markerade noden med noderna i det angivna [XPathNavigator](../)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ett [XPathNavigator](../)-objekt som är placerat på noden som ska läggas till som den nya syskonnoden. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlWriter](../../../system.xml/xmlwriter/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)