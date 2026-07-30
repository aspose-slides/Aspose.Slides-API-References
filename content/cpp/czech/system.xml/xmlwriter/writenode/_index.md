---
title: WriteNode()
second_title: Aspose.Slides pro C++ API Reference
description: Když je v odvozené třídě přepsána, zkopíruje vše z čtečky do zapisovače a přesune čtečku na začátek následujícího sourozence.
type: docs
weight: 430
url: /cs/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method

Když je v odvozené třídě přepsána, zkopíruje vše z čtečky do zapisovače a přesune čtečku na začátek následujícího sourozence.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) pro čtení. |
| defattr | **bool** | **true** pro zkopírování výchozích atributů z [XmlReader](../../xmlreader/); jinak **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method

Zkopíruje vše z objektu XPathNavigator do zapisovače. Pozice XPathNavigatoru zůstane beze změny.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | XPathNavigator pro kopírování. |
| defattr | **bool** | **true** pro zkopírování výchozích atributů; jinak **false**. |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [XmlReader](../../xmlreader/)
* Třída [XmlWriter](../)
* Třída [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)