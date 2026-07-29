---
title: BindingFlags
second_title: Aspose.Slides för C++ API-referens
description: Definierar medlemmar och typer för uppslagningslägen och bindningar.
type: docs
weight: 157
url: /sv/system.reflection/bindingflags/
---
## BindingFlags enum

Definierar medlemmar och typer för uppslagningslägen och bindningar.

```cpp
enum class BindingFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | 0 | Inga speciella alternativ. |
| IgnoreCase | 1 | Ignorera skiftläget i namn när du söker efter objektet. |
| DeclaredOnly | 2 | Sök endast efter medlemmar som deklarerats i typen och inte i basklasser. |
| Instance | 4 | Gå igenom instansmedlemmar. |
| Static | 8 | Gå igenom statiska medlemmar. |
| Public | 16 | Gå igenom offentliga medlemmar. |
| NonPublic | 32 | Gå igenom icke-offentliga medlemmar. |
| FlattenHierarchy | 64 | Gå igenom basklassens offentliga och skyddade statiska medlemmar. |
| InvokeMethod | 256 | Anropar metod. |
| CreateInstance | 512 | Skapar en reflekterad typinstans. |
| GetField | 1024 | Hämtar fältvärde. |
| SetField | 2048 | Sätter fältvärde. |
| GetProperty | 4096 | Hämtar egenskapsvärde. |
| SetProperty | 8192 | Sätter egenskapsvärde. |
| PutDispProperty | 16384 | Sätter COM-egenskap. |
| PutRefDispProperty | 32768 | Sätter COM-referensegenskap. |
| ExactBinding | 65536 | Typbindning måste vara exakt, utan några typändringar. |
| SuppressChangeType | 131072 | Stöds inte. |
| OptionalParamBinding | 262144 | Väljer överlagring baserat på antal argument. |
| IgnoreReturn | 16777216 | Ignorerar COM-interoperabilitetens returvärde. |

## Se även

* Namnrymd [System::Reflection](../)
* Bibliotek [Aspose.Slides](../../)