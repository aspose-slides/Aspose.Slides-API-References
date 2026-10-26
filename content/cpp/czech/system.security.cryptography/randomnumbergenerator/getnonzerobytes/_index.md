---
title: GetNonZeroBytes()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vyplní existující prvky pole náhodnými nenulovými bajty.
type: docs
weight: 27
url: /cs/system.security.cryptography/randomnumbergenerator/getnonzerobytes/
---
## RandomNumberGenerator::GetNonZeroBytes(ArrayPtr\<uint8_t\>) metoda

Vyplní existující prvky pole náhodnými nenulovými bajty.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů k vyplnění. |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView\<uint8_t\>) metoda

Vyplní existující prvky pohledu na pole náhodnými nenulovými bajty.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Pohled na pole bajtů k vyplnění. |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray\<uint8_t, N\>\&) metoda

Vyplní existující prvky zásobníkového pole náhodnými nenulovými bajty.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Pole zásobníku bajtů k vyplnění. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [RandomNumberGenerator](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)