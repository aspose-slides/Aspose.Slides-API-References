---
title: MoveToNextNamespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer dit wordt overschreven in een afgeleide klasse, verplaatst het XPathNavigator naar het volgende namespace-knooppunt dat overeenkomt met de opgegeven XPathNamespaceScope.
type: docs
weight: 573
url: /nl/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) methode

Wanneer dit wordt overschreven in een afgeleide klasse, verplaatst het [XPathNavigator](../) naar de volgende namespace-knooppunt die overeenkomt met de opgegeven XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Een XPathNamespaceScope-waarde die de namespace-scope beschrijft. |

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol wordt verplaatst naar het volgende namespace-knooppunt; anders **false**. Als **false**, blijft de positie van de [XPathNavigator](../) ongewijzigd.

## XPathNavigator::MoveToNextNamespace() methode

Verplaatst de [XPathNavigator](../) naar het volgende namespace-knooppunt.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### Retourwaarde

**true** als de [XPathNavigator](../) succesvol wordt verplaatst naar het volgende namespace-knooppunt; anders **false**. Als **false**, blijft de positie van de [XPathNavigator](../) ongewijzigd.

## Zie ook

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Klasse [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)