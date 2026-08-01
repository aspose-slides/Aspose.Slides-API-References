---
title: InsertBefore()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een XmlWriter-object dat wordt gebruikt om een nieuw broederknooppunt vóór het momenteel geselecteerde knooppunt te maken.
type: docs
weight: 911
url: /nl/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() methode

Retourneert een [XmlWriter](../../../system.xml/xmlwriter/)-object dat wordt gebruikt om een nieuw broederknooppunt vóór het momenteel geselecteerde knooppunt te maken.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Retourwaarde

Een [XmlWriter](../../../system.xml/xmlwriter/)-object dat wordt gebruikt om een nieuw broederknooppunt vóór het momenteel geselecteerde knooppunt te maken.

## XPathNavigator::InsertBefore(String) methode

Maakt een nieuw broederknooppunt vóór het momenteel geselecteerde knooppunt met behulp van de opgegeven XML-string.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | De XML-dataketen voor het nieuwe broederknooppunt. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) methode

Maakt een nieuw broederknooppunt vóór het momenteel geselecteerde knooppunt met behulp van de XML-inhoud van het opgegeven [XmlReader](../../../system.xml/xmlreader/)-object.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Een [XmlReader](../../../system.xml/xmlreader/)-object dat gepositioneerd is op de XML-gegevens voor het nieuwe broederknooppunt. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) methode

Maakt een nieuw broederknooppunt vóór het momenteel geselecteerde knooppunt met behulp van de knooppunten in het opgegeven [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Een [XPathNavigator](../)-object dat gepositioneerd is op het knooppunt dat moet worden toegevoegd als nieuw broederknooppunt. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Naamruimte [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)