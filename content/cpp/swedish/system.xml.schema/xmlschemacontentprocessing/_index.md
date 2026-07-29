---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller information om valideringsläget för any- och anyAttribute-elementers ersättningar.
type: docs
weight: 976
url: /sv/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Tillhandahåller information om valideringsläget för **any**- och **anyAttribute**-elementers ersättningar.

```cpp
enum class XmlSchemaContentProcessing
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Dokumentobjekt valideras inte. |
| Skip | 1 | Dokumentobjekt måste bestå av välformad XML och valideras inte av schemat. |
| Lax | 2 | Om det associerade schemat hittas kommer dokumentobjekten att valideras. Inga fel kommer att kastas annars. |
| Strict | 3 | Schemaprocessorn måste hitta ett schema som är kopplat till den angivna namnrymden för att validera dokumentobjekten. |

## Se även

* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)