---
title: CompareOrdinal()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två strängar med mindre-lika-större i ordinalt läge.
type: docs
weight: 833
url: /sv/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) metod

Jämför två strängar med mindre-lika-större i ordinalt läge.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| strB | const [String](../)\& | Andra strängen att jämföra. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) metod

Jämför två strängar med mindre-lika-större i ordinalt läge.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| indexA | int | Begynnelse på första strängens delsträng. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| indexB | int | Begynnelse på den andra strängens delsträng. |
| length | int | Antal tecken att jämföra. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## Se även

* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)