---
title: AddNamespace()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt de opgegeven namespace toe aan de collectie.
type: docs
weight: 66
url: /nl/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) methode

Voegt de opgegeven namespace toe aan de collectie.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | De prefix die moet worden geassocieerd met de toe te voegen namespace. Gebruik [String::Empty](../../../system/string/empty/) om een standaardnamespace toe te voegen. Als de [XmlNamespaceManager](../) zal worden gebruikt voor het oplossen van namespaces in een XML Path Language ([XPath](../../../system.xml.xpath/)) expressie, moet een prefix worden opgegeven. Als een [XPath](../../../system.xml.xpath/) expressie geen prefix bevat, wordt aangenomen dat de Uniform Resource Identifier (URI) van de namespace de lege namespace is. Voor meer informatie over [XPath](../../../system.xml.xpath/) expressies en de [XmlNamespaceManager](../), raadpleeg de methoden XmlNode::SelectNodes(String) en XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) . |
| uri | [String](../../../system/string/) | De toe te voegen namespace. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)