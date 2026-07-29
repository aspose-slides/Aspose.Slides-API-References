---
title: ValidationType
second_title: Aspose.Slides för C++ API-referens
description: Anger vilken typ av validering som ska utföras.
type: docs
weight: 729
url: /sv/system.xml/validationtype/
---
## ValidationType enum


Anger vilken typ av validering som ska utföras.

```cpp
enum class ValidationType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Ingen validering utförs, och inga valideringsfel kastas. Denna inställning skapar en XML 1.0-kompatibel icke-validerande parser. |
| Auto | 1 | Validerar om DTD- eller schemainformation hittas. |
| DTD | 2 | Validerar enligt DTD:n. |
| XDR | 3 | Validera enligt XML-Data Reduced (XDR)-scheman, inklusive inbäddade XDR-scheman. XDR-scheman identifieras med prefixet **x-schema** för namnrymd eller med [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/)-värdet. |
| Schema | 4 | Validera enligt XML [Schema](../../system.xml.schema/) definition language (XSD)-scheman, inklusive inbäddade XML-scheman. XML-scheman associeras med namnrymds-URI:er antingen genom att använda attributet **schemaLocation** eller de tillhandahållna **Schemas**. |

## Se även

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)