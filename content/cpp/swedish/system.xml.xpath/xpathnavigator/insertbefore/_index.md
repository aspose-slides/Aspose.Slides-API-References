---
title: InsertBefore()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett XmlWriter-objekt som används för att skapa en ny syskonnod före den för närvarande markerade noden.
type: docs
weight: 911
url: /sv/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() metod


Returnerar ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod före den för närvarande markerade noden.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### Return Value

Ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod före den för närvarande markerade noden.

## XPathNavigator::InsertBefore(String) metod


Skapar en ny syskonnod före den för närvarande markerade noden med den specificerade XML-strängen.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | XML-datatsträngen för den nya syskonnoden. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) metod


Skapar en ny syskonnod före den för närvarande markerade noden med XML-innehållet i det specificerade [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt placerat på XML-data för den nya syskonnoden. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) metod


Skapar en ny syskonnod före den för närvarande markerade noden med noderna i den specificerade [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ett [XPathNavigator](../)-objekt placerat på noden som ska läggas till som den nya syskonnoden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlWriter](../../../system.xml/xmlwriter/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)