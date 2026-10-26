---
title: LookupNamespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de namespace-URI voor de opgegeven prefix.
type: docs
weight: 118
url: /nl/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) methode

Retourneert de namespace-URI voor de opgegeven prefix.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | De prefix waarvan u de namespace-URI wilt oplossen. Om overeen te komen met de standaardnamespace, geeft u [String::Empty](../../../system/string/empty/) door. |

### Retourwaarde

De namespace-URI voor **prefix** of **nullptr** als er geen toegewezen namespace is. De geretourneerde string is geatomiseerd. Voor meer informatie over geatomiseerde strings, zie de [XmlNameTable](../../xmlnametable/) klasse.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)