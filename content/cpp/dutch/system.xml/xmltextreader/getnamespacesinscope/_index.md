---
title: GetNamespacesInScope()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een collectie die alle momenteel in scope naamruimtes bevat.
type: docs
weight: 716
url: /nl/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) methode


Retourneert een verzameling die alle momenteel in scope naamruimten bevat.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Een XmlNamespaceScope-waarde die het type naamruimtenodes specificeert dat moet worden geretourneerd. |

### Retourwaarde

Een IDictionary-object dat alle huidige in scope naamruimten bevat. Als de lezer niet op een element staat, wordt een lege dictionary (geen naamruimten) geretourneerd.

## Zie ook

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)