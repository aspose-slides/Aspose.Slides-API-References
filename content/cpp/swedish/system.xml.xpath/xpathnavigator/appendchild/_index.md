---
title: AppendChild()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett XmlWriter-objekt som används för att skapa ett eller flera nya barnnoder i slutet av listan över barnnoder för den aktuella noden.
type: docs
weight: 885
url: /sv/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metod

Returnerar ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa ett eller flera nya barnnoder i slutet av listan över barnnoder för den aktuella noden.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Returvärde

Ett [XmlWriter](../../../system.xml/xmlwriter/)-objekt som används för att skapa nya barnnoder i slutet av listan över barnnoder för den aktuella noden.

## XPathNavigator::AppendChild(String) metod

Skapar en ny barnnod i slutet av listan över barnnoder för den aktuella noden med den angivna XML-datametstringen.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | XML-datametstringen för den nya barnnoden. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metod

Skapar en ny barnnod i slutet av listan över barnnoder för den aktuella noden med XML-innehållet i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt placerat på XML-data för den nya barnnoden. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metod

Skapar en ny barnnod i slutet av listan över barnnoder för den aktuella noden med noderna i det angivna [XPathNavigator](../)-objektet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ett [XPathNavigator](../)-objekt placerat på noden som ska läggas till som den nya barnnoden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlWriter](../../../system.xml/xmlwriter/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)