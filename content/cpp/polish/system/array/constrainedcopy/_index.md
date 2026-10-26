---
title: ConstrainedCopy()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Kopiuje zakres elementów z System.Array zaczynając od określonego źródła.
type: docs
weight: 716
url: /pl/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Kopiuje zakres elementów z [System.Array](../) zaczynając od określonego źródła.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w tablicy źródłowej |
| DstType | Typ elementów w tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej wskazujący początek zakresu elementów do skopiowania |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej, od którego rozpocząć wstawianie skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Uwagi

TYMCZASOWA SUROWA IMPLEMENTACJA BEZ JAKICHKOLWIEK POPRAWEK!

## Zobacz także

* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)