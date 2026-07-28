---
title: Read()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje określoną liczbę bajtów z podłączonego strumienia i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 53
url: /pl/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów z podłączonego strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** liczona od zera, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów z podłączonego strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** liczona od zera, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BufferedStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)