---
title: Write()
second_title: Aspose.Slides dla C++ Referencja API
description: Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.
type: docs
weight: 209
url: /pl/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba elementów w podzakresie do zapisania. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisania |
| offset | **int32_t** | Indeks elementu w **buffer**, liczony od zera, w którym rozpoczyna się podzakres do zapisania |
| size | **int32_t** | Liczba elementów w podzakresie do zapisania |

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [NetworkStream](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)