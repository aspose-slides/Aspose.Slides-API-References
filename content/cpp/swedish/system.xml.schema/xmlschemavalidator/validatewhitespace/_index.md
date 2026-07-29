---
title: ValidateWhitespace()
second_title: Aspose.Slides för C++ API-referens
description: Validerar om blanktecken i den angivna strängen är tillåtet i det aktuella elementets sammanhang, och samlar in blanktecknet för validering om det aktuella elementet har enkelt innehåll.
type: docs
weight: 196
url: /sv/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) metod

Validerar om blanktecken i den angivna **string** är tillåtet i det aktuella elementets sammanhang, och samlar in blanktecknet för validering om det aktuella elementet har enkelt innehåll.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Ett blanktecken **string** att validera i det aktuella elementets sammanhang. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) metod

Validerar om blanktecken som returneras av det angivna XmlValueGetter-objektet är tillåtet i det aktuella elementets sammanhang, och samlar in blanktecknet för validering om det aktuella elementet har enkelt innehåll.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | En XmlValueGetter-återuppringning som används för att skicka blankteckenvärdet som en typ kompatibel med XML [Schema](../../) Definition Language (XSD) typ av attributet. |

## Se även

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaValidator](../)
* Namnrymd [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)