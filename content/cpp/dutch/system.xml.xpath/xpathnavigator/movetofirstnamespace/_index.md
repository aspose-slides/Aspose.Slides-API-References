---
title: MoveToFirstNamespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, verplaatst het XPathNavigator naar de eerste namespaceknoop die overeenkomt met de opgegeven XPathNamespaceScope.
type: docs
weight: 560
url: /nl/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) methode

Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](../) naar de eerste namespaceknoop die overeenkomt met de opgegeven XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Een XPathNamespaceScope-waarde die de namespace-scope beschrijft. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol verplaatst naar de eerste namespaceknoop; anders **false**. Als **false**, blijft de positie van de [XPathNavigator](../) ongewijzigd.

## XPathNavigator::MoveToFirstNamespace() methode

Verplaatst de [XPathNavigator](../) naar de eerste namespaceknoop van het huidige knooppunt.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol verplaatst naar de eerste namespaceknoop; anders **false**. Als **false**, blijft de positie van de [XPathNavigator](../) ongewijzigd.

## Zie ook

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* klasse [XPathNavigator](../)
* naamruimte [System::Xml::XPath](../../)
* bibliotheek [Aspose.Slides](../../../)