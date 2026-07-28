---
title: Read()
second_title: Aspose.Slides – dokumentacja API C++
description: Odczytuje dane ze strumienia.
type: docs
weight: 14
url: /pl/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje dane ze strumienia.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Docelowy bufor danych. |
| offset | **int32_t** | Przesunięcie w docelowym buforze. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Rzeczywista liczba odczytywanych bajtów.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje dane ze strumienia.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Docelowy bufor danych. |
| offset | **int32_t** | Przesunięcie w docelowym buforze. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Rzeczywista liczba odczytywanych bajtów.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [CryptoStream](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)