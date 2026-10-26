---
title: WriteNode()
second_title: Aspose.Slides för C++ API-referens
description: När den överskrivs i en avledd klass kopierar den allt från läsaren till skrivaren och flyttar läsaren till början av nästa syskon.
type: docs
weight: 430
url: /sv/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) metod

När den överskrivs i en avledd klass kopierar den allt från läsaren till skrivaren och flyttar läsaren till början av nästa syskon.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Den [XmlReader](../../xmlreader/) att läsa från. |
| defattr | **bool** | **true** för att kopiera standardattributen från [XmlReader](../../xmlreader/); annars **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) metod

Kopierar allt från XPathNavigator-objektet till skrivaren. Positionen för XPathNavigator förblir oförändrad.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | XPathNavigator att kopiera från. |
| defattr | **bool** | **true** för att kopiera standardattributen; annars **false**. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlReader](../../xmlreader/)
* Klass [XmlWriter](../)
* Klass [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)