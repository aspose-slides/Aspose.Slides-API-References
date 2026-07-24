---
title: idx_get()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt das XmlSchema zurück, das mit dem angegebenen Namespace-URI verknüpft ist.
type: docs
weight: 53
url: /de/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) Methode

Gibt das [XmlSchema](../../xmlschema/) zurück, das mit dem angegebenen Namespace-URI verknüpft ist.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Schema zugeordnet ist, das Sie zurückgeben möchten. Dies ist typischerweise das **targetNamespace** des Schemas. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/) für den Namespace-URI; **nullptr**, falls kein geladenes Schema dem angegebenen Namespace zugeordnet ist oder wenn der Namespace einem XDR-Schema zugeordnet ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaCollection](../)
* Namensraum [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)