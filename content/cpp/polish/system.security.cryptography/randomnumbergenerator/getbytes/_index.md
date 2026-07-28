---
title: GetBytes()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wypełnia istniejące elementy tablicy losowymi bajtami.
type: docs
weight: 14
url: /pl/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metoda


Zapełnia istniejące elementy tablicy losowymi bajtami.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes array to fill. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metoda


Zapełnia istniejący fragment tablicy losowymi bajtami.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes array to fill slice of. |
| offset | int | Slice beginning index. |
| count | int | Slice size. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metoda


Zapełnia istniejące elementy widoku tablicy losowymi bajtami.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Bytes array view to fill. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metoda


Zapełnia istniejący fragment widoku tablicy losowymi bajtami.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Bytes array view to fill slice of. |
| offset | int | Slice beginning index. |
| count | int | Slice size. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metoda


Zapełnia istniejące elementy stosowej tablicy losowymi bajtami.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Bytes stack array to fill. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metoda


Zapełnia istniejący fragment stosowej tablicy losowymi bajtami.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Bytes stack array to fill slice of. |
| offset | int | Slice beginning index. |
| count | int | Slice size. |

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [RandomNumberGenerator](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)