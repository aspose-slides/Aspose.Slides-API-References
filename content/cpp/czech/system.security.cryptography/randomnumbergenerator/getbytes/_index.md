---
title: GetBytes()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vyplní existující prvky pole náhodnými bajty.
type: docs
weight: 14
url: /cs/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metoda

Vyplní existující prvky pole náhodnými bajty.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů k vyplnění. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metoda

Vyplní existující část pole náhodnými bajty.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů k vyplnění části. |
| offset | int | Počáteční index řezu. |
| count | int | Velikost řezu. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metoda

Vyplní existující prvky pohledu na pole náhodnými bajty.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Pohled na pole bajtů k vyplnění. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metoda

Vyplní existující část pohledu na pole náhodnými bajty.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Pohled na pole bajtů k vyplnění části. |
| offset | int | Počáteční index řezu. |
| count | int | Velikost řezu. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metoda

Vyplní existující prvky stack pole náhodnými bajty.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Stack pole bajtů k vyplnění. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metoda

Vyplní existující část stack pole náhodnými bajty.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Stack pole bajtů k vyplnění části. |
| offset | int | Počáteční index řezu. |
| count | int | Velikost řezu. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [RandomNumberGenerator](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)