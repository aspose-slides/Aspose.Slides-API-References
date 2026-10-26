---
title: ValidateText()
second_title: Aspose.Slides för C++ API-referens
description: Validerar om den angivna textsträngen är tillåten i det aktuella elementets sammanhang, och samlar texten för validering om det aktuella elementet har enkelt innehåll.
type: docs
weight: 183
url: /sv/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) metod

Validerar om den angivna **string** är tillåten i det aktuella elementets sammanhang och samlar texten för validering om det aktuella elementet har enkelt innehåll.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | En **string** som ska valideras i det aktuella elementets sammanhang. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) metod

Validerar om den text som returneras av det angivna XmlValueGetter-objektet är tillåten i det aktuella elementets sammanhang, och samlar texten för validering om det aktuella elementet har enkelt innehåll.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | En XmlValueGetter-callback som används för att skicka textvärdet som en typ kompatibel med XML [Schema](../../) Definition Language (XSD)-typen för attributet. |

## Se också

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaValidator](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)