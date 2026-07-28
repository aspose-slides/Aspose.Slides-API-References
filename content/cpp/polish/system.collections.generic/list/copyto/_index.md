---
title: CopyTo()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Kopiuje elementy listy do istniejących elementów tablicy.
type: docs
weight: 209
url: /pl/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metoda

Kopiuje elementy listy do istniejących elementów tablicy.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Tablica docelowa. |
| arrayIndex | int | Początkowy indeks tablicy docelowej. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metoda

Kopiuje wszystkie elementy do istniejących elementów tablicy.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) do skopiowania elementów. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metoda

Kopiuje elementy zaczynając od określonego indeksu do istniejących elementów tablicy.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks (liczony od zera) elementu w liście reprezentowanej przez bieżący obiekt, od którego rozpocząć kopiowanie |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) do skopiowania elementów. |
| arrayIndex | int | Początkowa pozycja w tablicy docelowej. |
| count | int | Liczba elementów do skopiowania. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [List](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)