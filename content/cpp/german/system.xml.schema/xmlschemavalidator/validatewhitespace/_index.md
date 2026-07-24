---
title: ValidateWhitespace()
second_title: Aspose.Slides für C++ API Referenz
description: Validiert, ob das im angegebenen String enthaltene Leerzeichen im aktuellen Elementkontext zulässig ist und sammelt das Leerzeichen zur Validierung, falls das aktuelle Element einfachen Inhalt hat.
type: docs
weight: 196
url: /de/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) Methode

Validiert, ob das im angegebenen **string** enthaltene Leerzeichen im aktuellen Elementkontext zulässig ist und sammelt das Leerzeichen zur Validierung, falls das aktuelle Element einfachen Inhalt hat.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Ein Leerzeichen-**string**, das im aktuellen Elementkontext zu validieren ist. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) Methode

Validiert, ob das vom angegebenen XmlValueGetter-Objekt zurückgegebene Leerzeichen im aktuellen Elementkontext zulässig ist und sammelt das Leerzeichen zur Validierung, falls das aktuelle Element einfachen Inhalt hat.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Ein XmlValueGetter-Callback, der verwendet wird, um den Leerzeichenwert als mit der XML [Schema](../../) Definition Language (XSD)-Typ des Attributs kompatiblen Typ zu übergeben. |

## Siehe auch

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)