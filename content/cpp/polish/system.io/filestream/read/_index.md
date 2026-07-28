---
title: Read()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je w podanej tablicy bajtów.
type: docs
weight: 183
url: /pl/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je w podanej tablicy bajtów.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty. |
| offset | **int32_t** | Pozycja bazująca na 0 w **buffer**, od której rozpocząć zapisywanie. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Liczba odczytanych bajtów.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je w podanej tablicy bajtów.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów, do którego zapisywane są odczytane bajty. |
| offset | **int32_t** | Pozycja bazująca na 0 w **buffer**, od której rozpocząć zapisywanie. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Liczba odczytanych bajtów.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [FileStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)