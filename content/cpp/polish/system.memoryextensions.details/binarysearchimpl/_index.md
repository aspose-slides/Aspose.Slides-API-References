---
title: BinarySearchImpl()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Standardowa implementacja wyszukiwania binarnego.
type: docs
weight: 118
url: /pl/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) funkcja

Standardowa implementacja wyszukiwania binarnego.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w span |
| TValue | Typ wartości do wyszukania |
| TCompareFunc | Typ funkcji do porównania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span do przeszukania |
| value | const TValue\& | Wartość do wyszukania |
| compareFunc | TCompareFunc | Funkcja porównująca wartość z elementem span i zwracająca **int32_t** (-1, 0, 1) |

### Wartość zwracana

[Index](../../system/index/) elementu znalezionego lub dopełnienie bitowe punktu wstawienia

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)