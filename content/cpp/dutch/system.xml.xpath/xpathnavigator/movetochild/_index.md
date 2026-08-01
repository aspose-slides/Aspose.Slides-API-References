---
title: MoveToChild()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst de XPathNavigator naar het kindknooppunt met de opgegeven lokale naam en namespace-URI.
type: docs
weight: 690
url: /nl/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) methode

Verplaatst de [XPathNavigator](../) naar het kindknooppunt met de opgegeven lokale naam en namespace-URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het kindknooppunt waarnaar verplaatst wordt. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het kindknooppunt waarnaar verplaatst wordt. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol naar het kindknooppunt verplaatst; anders **false**. Als **false**, blijft de positie van de [XPathNavigator](../) ongewijzigd.

## XPathNavigator::MoveToChild(XPathNodeType) methode

Verplaatst de [XPathNavigator](../) naar het kindknooppunt van het opgegeven XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van het kindknooppunt waarnaar verplaatst wordt. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol naar het kindknooppunt verplaatst; anders **false**. Als **false**, blijft de positie van de [XPathNavigator](../) ongewijzigd.

## Zie ook

* Enum [XPathNodeType](../../xpathnodetype/)
* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)