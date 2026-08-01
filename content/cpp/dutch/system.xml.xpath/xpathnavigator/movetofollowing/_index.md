---
title: MoveToFollowing()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst de XPathNavigator naar het element met de opgegeven lokale naam en namespace-URI in documentvolgorde.
type: docs
weight: 703
url: /nl/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) methode


Verplaatst de [XPathNavigator](../) naar het element met de opgegeven lokale naam en namespace-URI in documentvolgorde.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het element. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het element. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol verplaatst is; anders **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) methode


Verplaatst de [XPathNavigator](../) naar het element met de opgegeven lokale naam en namespace-URI, tot de opgegeven grens, in documentvolgorde.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het element. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het element. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Het [XPathNavigator](../)-object gepositioneerd op de elementgrens waardoor de huidige [XPathNavigator](../) niet voorbij zal gaan tijdens het zoeken naar het volgende element. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol verplaatst is; anders **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) methode


Verplaatst de [XPathNavigator](../) naar het volgende element van het opgegeven XPathNodeType in documentvolgorde.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van het element. Het XPathNodeType mag niet [XPathNodeType::Attribute](../../xpathnodetype/) of [XPathNodeType::Namespace](../../xpathnodetype/) zijn. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol verplaatst is; anders **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) methode


Verplaatst de [XPathNavigator](../) naar het volgende element van het opgegeven XPathNodeType, tot de opgegeven grens, in documentvolgorde.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van het element. Het XPathNodeType mag niet [XPathNodeType::Attribute](../../xpathnodetype/) of [XPathNodeType::Namespace](../../xpathnodetype/) zijn. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Het [XPathNavigator](../)-object gepositioneerd op de elementgrens waardoor de huidige [XPathNavigator](../) niet voorbij zal gaan tijdens het zoeken naar het volgende element. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol verplaatst is; anders **false**.

## Zie ook

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)