---
title: ValidateAttribute()
second_title: Aspose.Slides für C++ API Referenz
description: Validiert den Attributnamen, den Namespace-URI und den Wert im aktuellen Elementkontext.
type: docs
weight: 144
url: /de/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) Methode

Validiert den Attributnamen, den Namespace-URI und den Wert im aktuellen Elementkontext.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des zu validierenden Attributs. |
| namespaceUri | const [String](../../../system/string/)\& | Der Namespace-URI des zu validierenden Attributs. |
| attributeValue | const [String](../../../system/string/)\& | Der Wert des zu validierenden Attributs. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ein [XmlSchemaInfo](../../xmlschemainfo/)-Objekt, dessen Eigenschaften bei erfolgreicher Validierung des Attributs gesetzt werden. Dieser Parameter kann **nullptr** sein. |

### Rückgabewert

Der Wert des validierten Attributs.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) Methode

Validiert den Attributnamen, den Namespace-URI und den Wert im aktuellen Elementkontext.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des zu validierenden Attributs. |
| namespaceUri | const [String](../../../system/string/)\& | Der Namespace-URI des zu validierenden Attributs. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Ein XmlValueGetter-Callback, der verwendet wird, um den Wert des Attributs als einen mit dem XML [Schema](../../) Definition Language (XSD)-Typ des Attributs kompatiblen Typ zu übergeben. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ein [XmlSchemaInfo](../../xmlschemainfo/)-Objekt, dessen Eigenschaften bei erfolgreicher Validierung des Attributs gesetzt werden. Dieser Parameter kann **nullptr** sein. |

### Rückgabewert

Der Wert des validierten Attributs.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaInfo](../../xmlschemainfo/)
* Klasse [XmlSchemaValidator](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)