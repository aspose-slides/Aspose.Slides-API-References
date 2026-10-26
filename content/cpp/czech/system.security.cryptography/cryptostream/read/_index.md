---
title: Read()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Čte data ze streamu.
type: docs
weight: 14
url: /cs/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Čte data ze streamu.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Cílový datový buffer. |
| offset | **int32_t** | Posun v cílovém bufferu. |
| count | **int32_t** | Počet bajtů k přečtení. |

### Návratová hodnota

Skutečný počet přečtených bajtů.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Čte data ze streamu.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Cílový datový buffer. |
| offset | **int32_t** | Posun v cílovém bufferu. |
| count | **int32_t** | Počet bajtů k přečtení. |

### Návratová hodnota

Skutečný počet přečtených bajtů.

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [CryptoStream](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)