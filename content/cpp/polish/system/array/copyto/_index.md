---
title: CopyTo()
second_title: Referencja API Aspose.Slides dla C++
description: Kopiuje wszystkie elementy bieżącej tablicy do określonej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem arrayIndex.
type: docs
weight: 118
url: /pl/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metoda

Kopiuje wszystkie elementy bieżącej tablicy do określonej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Tablica docelowa |
| arrayIndex | int | [Index](../../index/) w tablicy docelowej, aby rozpocząć wstawianie skopiowanych elementów |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metoda

Kopiuje wszystkie elementy bieżącej tablicy do określonej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| DstType | Typ elementów w tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej, aby rozpocząć wstawianie skopiowanych elementów |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metoda

Kopiuje wszystkie elementy bieżącej tablicy do określonego widoku tablicy docelowej. Elementy są wstawiane do widoku tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| DstType | Typ elementów w widoku tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Widok tablicy docelowej |
| dstIndex | **int64_t** | [Index](../../index/) w widoku tablicy docelowej, aby rozpocząć wstawianie skopiowanych elementów |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metoda

Kopiuje określoną liczbę elementów z bieżącej tablicy, zaczynając od określonej pozycji, do określonej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| DstType | Typ elementów w tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej, aby rozpocząć kopiowanie elementów |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej, aby rozpocząć wstawianie skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metoda

Kopiuje określoną liczbę elementów z bieżącej tablicy, zaczynając od określonej pozycji, do określonego widoku tablicy docelowej. Elementy są wstawiane do widoku tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| DstType | Typ elementów w widoku tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Widok tablicy docelowej |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej, aby rozpocząć kopiowanie elementów |
| dstIndex | **int64_t** | [Index](../../index/) w widoku tablicy docelowej, aby rozpocząć wstawianie skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Zobacz także

* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)