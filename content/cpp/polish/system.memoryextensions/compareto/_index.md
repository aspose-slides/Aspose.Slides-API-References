---
title: CompareTo()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Porównuje dwa zakresy znaków przy użyciu określonych reguł porównywania ciągów.
type: docs
weight: 404
url: /pl/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkcja


Porównuje dwa zakresy znaków przy użyciu określonych reguł porównywania ciągów.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Pierwszy zakres znaków |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Drugi zakres znaków |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porównywania ciągów, które ma zostać wykonane |

### Wartość zwracana

Ujemna wartość, jeśli span < other, zero, jeśli są równe, dodatnia, jeśli span > other

## Zobacz także

* Wyliczenie [StringComparison](../../system/stringcomparison/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)