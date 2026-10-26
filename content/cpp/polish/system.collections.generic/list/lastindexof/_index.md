---
title: LastIndexOf()
second_title: Aspose.Slides dla C++ - referencja API
description: Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w całej liście.
type: docs
weight: 469
url: /pl/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const metoda


Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w całej liście.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const T\& | Obiekt do zlokalizowania w liście |

### Wartość zwracana

Indeks zerowy ostatniego wystąpienia elementu w całym [List](../), jeśli zostanie znaleziony; w przeciwnym razie -1.

## List::LastIndexOf(const T\&, int32_t) const metoda


Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w zakresie elementów w [List](../), który rozciąga się od pierwszego elementu do określonego indeksu.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const T\& | Obiekt do zlokalizowania w liście |
| index | **int32_t** | Zerowy indeks początkowy wyszukiwania wstecz. |

### Wartość zwracana

Indeks zerowy ostatniego wystąpienia elementu w zakresie elementów w [List](../), który rozciąga się od pierwszego elementu do indeksu, jeśli zostanie znaleziony; w przeciwnym razie -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const metoda


Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w zakresie elementów w [List](../), który zawiera określoną liczbę elementów i kończy się na określonym indeksie.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const T\& | Obiekt do zlokalizowania w [List](../) |
| index | **int32_t** | Zerowy indeks początkowy wyszukiwania wstecz. |
| count | **int32_t** | Liczba elementów w sekcji do przeszukania. |

### Wartość zwracana

Indeks zerowy ostatniego wystąpienia elementu w zakresie elementów w [List](../), który zawiera liczbę elementów określoną przez count i kończy się na indeksie, jeśli zostanie znaleziony; w przeciwnym razie -1.

## Zobacz także

* Klasa [List](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)