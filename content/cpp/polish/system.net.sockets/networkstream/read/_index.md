---
title: Read()
second_title: Dokumentacja API Aspose.Slides for C++
description: Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 196
url: /pl/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, w której zostaną zapisane odczytane bajty. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Liczba odczytanych bajtów.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów, do którego zapisywane są odczytane bajty. |
| offset | **int32_t** | Pozycja bazująca na zerze w **buffer**, od której zaczyna się zapisywanie. |
| size | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [NetworkStream](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)