---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de XmlSchema die geassocieerd is met de opgegeven namespace-URI.
type: docs
weight: 53
url: /nl/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) methode

Retourneert de [XmlSchema](../../xmlschema/) die geassocieerd is met de opgegeven namespace-URI.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | De namespace-URI die geassocieerd is met het schema dat u wilt retourneren. Dit zal doorgaans de **targetNamespace** van het schema zijn. |

### Retourwaarde

De [XmlSchema](../../xmlschema/) die geassocieerd is met de namespace-URI; **nullptr** als er geen geladen schema is dat geassocieerd is met de gegeven namespace of als de namespace geassocieerd is met een XDR-schema.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaCollection](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)