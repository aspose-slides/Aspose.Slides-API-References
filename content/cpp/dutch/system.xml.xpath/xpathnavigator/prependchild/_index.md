---
title: PrependChild()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een XmlWriter-object dat wordt gebruikt om een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt te maken.
type: docs
weight: 872
url: /nl/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() methode

Retourneert een [XmlWriter](../../../system.xml/xmlwriter/) object dat wordt gebruikt om een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt te maken.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Retourwaarde

Een [XmlWriter](../../../system.xml/xmlwriter/) object dat wordt gebruikt om een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt te maken.

## XPathNavigator::PrependChild(String) methode

Maakt een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van de opgegeven XML-tekenreeks.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | De XML-datatekenreeks voor het nieuwe kindknooppunt. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) methode

Maakt een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van de XML-inhoud van het opgegeven [XmlReader](../../../system.xml/xmlreader/) object.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Een [XmlReader](../../../system.xml/xmlreader/) object gepositioneerd op de XML-gegevens voor het nieuwe kindknooppunt. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) methode

Maakt een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van de knooppunten in het opgegeven [XPathNavigator](../) object.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Een [XPathNavigator](../) object gepositioneerd op het knooppunt dat moet worden toegevoegd als nieuw kindknooppunt. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)