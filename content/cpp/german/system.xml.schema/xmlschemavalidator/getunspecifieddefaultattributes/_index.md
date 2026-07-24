---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides für C++ API-Referenz
description: "Validiert Identitätsbeschränkungen der Standardattribute und füllt die angegebene List mit XmlSchemaAttribute-Objekten für alle Attribute mit Standardwerten, die im Elementkontext noch nicht zuvor mit der XmlSchemaValidator::ValidateAttribute-Methode validiert wurden."
type: docs
weight: 157
url: /de/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) Methode

Validiert Identitätsbeschränkungen der Standardattribute und füllt die angegebene List mit [XmlSchemaAttribute](../../xmlschemaattribute/)-Objekten für alle Attribute mit Standardwerten, die im Elementkontext noch nicht mit der [XmlSchemaValidator::ValidateAttribute](../validateattribute/)-Methode validiert wurden.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Eine List, die mit [XmlSchemaAttribute](../../xmlschemaattribute/)-Objekten gefüllt werden soll für alle Attribute, die im Elementkontext noch nicht während der Validierung aufgetreten sind. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [List](../../../system.collections.generic/list/)
* Klasse [Object](../../../system/object/)
* Klasse [XmlSchemaValidator](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)