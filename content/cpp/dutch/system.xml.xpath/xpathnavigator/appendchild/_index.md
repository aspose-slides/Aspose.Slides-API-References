---
title: AppendChild()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een XmlWriter object dat wordt gebruikt om één of meer nieuwe kindknooppunten te maken aan het einde van de lijst met kindknooppunten van het huidige knooppunt.
type: docs
weight: 885
url: /nl/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() methode

Retourneert een [XmlWriter](../../../system.xml/xmlwriter/) object dat wordt gebruikt om één of meer nieuwe kindknooppunten te maken aan het einde van de lijst met kindknooppunten van het huidige knooppunt.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Retourwaarde

Een [XmlWriter](../../../system.xml/xmlwriter/) object dat wordt gebruikt om nieuwe kindknooppunten te maken aan het einde van de lijst met kindknooppunten van het huidige knooppunt.

## XPathNavigator::AppendChild(String) methode

Maakt een nieuw kindknooppunt aan het einde van de lijst met kindknooppunten van het huidige knooppunt met behulp van de opgegeven XML-datastring.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | De XML-datastring voor het nieuwe kindknooppunt. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) methode

Maakt een nieuw kindknooppunt aan het einde van de lijst met kindknooppunten van het huidige knooppunt met behulp van de XML-inhoud van het opgegeven [XmlReader](../../../system.xml/xmlreader/) object.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Een [XmlReader](../../../system.xml/xmlreader/) object gepositioneerd op de XML-gegevens voor het nieuwe kindknooppunt. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) methode

Maakt een nieuw kindknooppunt aan het einde van de lijst met kindknooppunten van het huidige knooppunt met behulp van de knooppunten in de opgegeven [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Een [XPathNavigator](../) object gepositioneerd op het knooppunt dat moet worden toegevoegd als het nieuwe kindknooppunt. |

## Zie Ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)