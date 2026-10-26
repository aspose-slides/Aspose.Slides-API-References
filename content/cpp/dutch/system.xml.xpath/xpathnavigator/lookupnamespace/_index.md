---
title: LookupNamespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de namespace-URI voor het opgegeven voorvoegsel.
type: docs
weight: 404
url: /nl/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) methode


Retourneert de namespace-URI voor het opgegeven voorvoegsel.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Het voorvoegsel waarvan u de namespace-URI wilt oplossen. Om overeen te komen met de standaard-namespace, geeft u [String::Empty](../../../system/string/empty/) door. |

### Retourwaarde

Een [String](../../../system/string/) die de namespace-URI bevat die is toegewezen aan het opgegeven namespace-voorvoegsel; **nullptr** als er geen namespace-URI is toegewezen aan het opgegeven voorvoegsel. De [String](../../../system/string/) die wordt geretourneerd is geatomiseerd.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)