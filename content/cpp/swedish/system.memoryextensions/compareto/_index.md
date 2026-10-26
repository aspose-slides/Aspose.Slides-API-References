---
title: CompareTo()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två teckenspan med angivna regler för strängjämförelse.
type: docs
weight: 404
url: /sv/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funktion

Jämför två teckenspan med angivna regler för strängjämförelse.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Det första teckenspan |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Det andra teckenspan |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ av strängjämförelse som ska utföras |

## Returvärde

Negativt värde om span < other, noll om lika, positivt om span > other

## Se även

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)