---
title: SetByte()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Interpretuj podaną tablicę typowaną jako surową tablicę bajtów i ustaw określoną wartość bajtu pod podanym offsetem bajtu.
type: docs
weight: 40
url: /pl/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method

Interpretuj podaną tablicę typowaną jako surową tablicę bajtów i ustawia określoną wartość bajtu pod podanym offsetem bajtu.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Tablica docelowa |
| index | int | Zero-oparty offset bajtu do ustawienia |
| value | **uint8_t** | Wartość bajtu do ustawienia |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method

Interpretuj podaną tablicę typowaną jako surową tablicę bajtów i ustawia określoną wartość bajtu pod podanym offsetem bajtu.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Widok docelowej tablicy |
| index | int | Zero-oparty offset bajtu do ustawienia |
| value | **uint8_t** | Wartość bajtu do ustawienia |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method

Interpretuj podaną tablicę typowaną jako surową tablicę bajtów i ustawia określoną wartość bajtu pod podanym offsetem bajtu.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy |
| N | Rozmiar tablicy stosu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Docelowa tablica stosu |
| index | int | Zero-oparty offset bajtu do ustawienia |
| value | **uint8_t** | Wartość bajtu do ustawienia |

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Array](../../array/)
* Klasa [Buffer](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)