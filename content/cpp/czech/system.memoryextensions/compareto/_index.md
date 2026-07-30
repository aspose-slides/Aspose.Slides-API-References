---
title: CompareTo()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává dva rozsahy znaků s určenými pravidly porovnání řetězců.
type: docs
weight: 404
url: /cs/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkce


Porovnává dva rozsahy znaků s určenými pravidly porovnání řetězců.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | První rozsah znaků |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Druhý rozsah znaků |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porovnání řetězce, které se provede |

### Návratová hodnota

Negativní hodnota, pokud je span < other, nula pokud jsou stejné, pozitivní hodnota, pokud je span > other

## Viz také

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)