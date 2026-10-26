---
title: GetNamespacesInScope()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een collectie van naamruimtenamen, waarbij de prefix als sleutel dient, die kan worden gebruikt om de momenteel geldende naamruimtes te enumereren.
type: docs
weight: 105
url: /nl/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) methode

Retourneert een collectie van naamruimtenamen, met een prefix als sleutel, die kan worden gebruikt om de naamruimtes die momenteel in scope zijn te enumereren.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Een enumeratiewaarde die het type naamruimteknooppunten specificeert dat moet worden geretourneerd. |

### Retourwaarde

Een collectie van naamruimte- en prefixparen die momenteel in scope zijn.

## Zie ook

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)