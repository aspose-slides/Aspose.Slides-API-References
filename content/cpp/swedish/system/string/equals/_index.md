---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Strängjämförelse för likhet. Flera lägen som tillhandahålls av StringComparison-enumerationen stöds.
type: docs
weight: 391
url: /sv/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const metod


[String](../) likhetsjämförelse. Flera lägen som tillhandahålls av StringComparison-enumerationen stöds.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) för att jämföra med den aktuella. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge (se [System::StringComparison](../../stringcomparison/) för detaljer). |

### Returvärde

true om strängarna matchar med den valda jämförelsetypen, annars false.

## String::Equals(const String\&) const metod


[String](../) likhetsjämförelse. Använder [System::StringComparison::Ordinal](../../stringcomparison/) jämförelseläge.

```cpp
bool System::String::Equals(const String &str) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) för att jämföra med den aktuella. |

### Returvärde

true om strängarna matchar, annars false.

## String::Equals(const String\&, const String\&) metod


Jämför två strängar med Ordial jämförelseläge.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| strB | const [String](../)\& | Andra strängen att jämföra. |

### Returvärde

true om strängarna matchar, annars false.

## String::Equals(const String\&, const String\&, System::StringComparison) metod


Jämför två strängar.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge. |

### Returvärde

true om strängarna matchar, annars false.

## Se även

* Enum [StringComparison](../../stringcomparison/)
* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)