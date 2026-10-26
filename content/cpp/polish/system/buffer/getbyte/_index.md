---
title: GetByte()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i pobierz wartość bajtu pod określonym przesunięciem bajtowym.
type: docs
weight: 27
url: /pl/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) metoda


Interpretuj wybraną tablicę typowaną jako surową tablicę bajtów i pobiera wartość bajtu pod określonym przesunięciem bajtowym.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Tablica docelowa |
| index | int | Zero-indeksowe przesunięcie bajtu do pobrania |

### Wartość zwracana

Wartość bajtu pod określonym indeksem

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) metoda


Interpretuj wybraną tablicę typowaną jako surową tablicę bajtów i pobiera wartość bajtu pod określonym przesunięciem bajtowym.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów widoku tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Widok docelowej tablicy |
| index | int | Zero-indeksowe przesunięcie bajtu do pobrania |

### Wartość zwracana

Wartość bajtu pod określonym indeksem

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) metoda


Interpretuj wybraną tablicę typowaną jako surową tablicę bajtów i pobiera wartość bajtu pod określonym przesunięciem bajtowym.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów stosowanej tablicy |
| N | Rozmiar stosowanej tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Docelowa tablica stosowa |
| index | int | Zero-indeksowe przesunięcie bajtu do pobrania |

### Wartość zwracana

Wartość bajtu pod określonym indeksem

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Array](../../array/)
* Klasa [Buffer](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)