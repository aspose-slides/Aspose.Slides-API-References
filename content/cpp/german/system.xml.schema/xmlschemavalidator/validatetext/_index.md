---
title: ValidateText()
second_title: Aspose.Slides für C++ API-Referenz
description: Validiert, ob die angegebene Textzeichenfolge im aktuellen Elementkontext zulässig ist und sammelt den Text zur Validierung, falls das aktuelle Element einfachen Inhalt hat.
type: docs
weight: 183
url: /de/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) Methode

Validiert, ob die angegebene Text **string** im aktuellen Elementkontext zulässig ist und sammelt den Text zur Validierung, falls das aktuelle Element einfachen Inhalt hat.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Ein Text **string**, das im aktuellen Elementkontext validiert werden soll. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) Methode

Validiert, ob der von dem angegebenen XmlValueGetter-Objekt zurückgegebene Text im aktuellen Elementkontext zulässig ist und sammelt den Text zur Validierung, falls das aktuelle Element einfachen Inhalt hat.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Ein XmlValueGetter-Callback, der den Textwert als mit dem XML [Schema](../../) Definition Language (XSD)-Typ des Attributs kompatiblen Typ übergibt. |

## Siehe auch

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaValidator](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)