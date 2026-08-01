---
title: InsertAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een XmlWriter-object dat wordt gebruikt om een nieuw broederknooppunt te maken na het momenteel geselecteerde knooppunt.
type: docs
weight: 898
url: /nl/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() methode

Retourneert een [XmlWriter](../../../system.xml/xmlwriter/) object dat wordt gebruikt om een nieuw broederknooppunt te maken na het momenteel geselecteerde knooppunt.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Retourwaarde

Een [XmlWriter](../../../system.xml/xmlwriter/) object dat wordt gebruikt om een nieuw broederknooppunt te maken na het momenteel geselecteerde knooppunt.

## XPathNavigator::InsertAfter(String) methode

Maakt een nieuw broederknooppunt na het momenteel geselecteerde knooppunt met behulp van de opgegeven XML-string.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | De XML-gegevensreeks voor het nieuwe broederknooppunt. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) methode

Maakt een nieuw broederknooppunt na het momenteel geselecteerde knooppunt met behulp van de XML-inhoud van het opgegeven [XmlReader](../../../system.xml/xmlreader/) object.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Een [XmlReader](../../../system.xml/xmlreader/) object gepositioneerd op de XML-gegevens voor het nieuwe broederknooppunt. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) methode

Maakt een nieuw broederknooppunt na het momenteel geselecteerde knooppunt met behulp van de knooppunten in het opgegeven [XPathNavigator](../) object.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Een [XPathNavigator](../) object gepositioneerd op het knooppunt dat moet worden toegevoegd als het nieuwe broederknooppunt. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Naamruimte [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)