---
title: Encrypt()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Szyfruje wiadomość. Nie zaimplementowano.
type: docs
weight: 118
url: /pl/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) metoda

Szyfruje wiadomość. Nie zaimplementowano.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) do zaszyfrowania. |
| use_oaep | **bool** | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### Wartość zwracana

Tablica zaszyfrowanych danych.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metoda

Szyfruje dane wejściowe przy użyciu określonego trybu wypełnienia.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tablica do zaszyfrowania. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Tryb wypełnienia. |

### Wartość zwracana

Zaszyfrowane dane w formacie tablicy bajtów.

## Zobacz także

* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [RSACryptoServiceProvider](../)
* Klasa [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)