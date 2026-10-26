---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa opcje walidacji schematu używane przez klasy XmlSchemaValidator i XmlReader.
type: docs
weight: 1054
url: /pl/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Określa opcje walidacji schematu używane przez klasy [XmlSchemaValidator](../xmlschemavalidator/) i [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Nie przetwarzaj ograniczeń tożsamości, wbudowanych schematów, wskazówek lokalizacji schematu ani nie zgłaszaj ostrzeżeń walidacji schematu. |
| ProcessInlineSchema | 1 | Przetwarzaj wbudowane schematy napotkane podczas walidacji. |
| ProcessSchemaLocation | 2 | Przetwarzaj wskazówki lokalizacji schematu (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) napotkane podczas walidacji. |
| ReportValidationWarnings | 4 | Zgłaszaj ostrzeżenia walidacji schematu napotkane podczas walidacji. |
| ProcessIdentityConstraints | 8 | Przetwarzaj ograniczenia tożsamości (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) napotkane podczas walidacji. |
| AllowXmlAttributes | 16 | Zezwalaj na atrybuty xml:* nawet jeśli nie są zdefiniowane w schemacie. Atrybuty będą walidowane na podstawie ich typu danych. |

## Zobacz także

* Przestrzeń nazw [System::Xml::Schema](../)
* Biblioteka [Aspose.Slides](../../)