---
title: Decrypt()
second_title: Aspose.Slides dla C++ – referencja API
description: Odszyfrowuje wiadomość. Nie zaimplementowano.
type: docs
weight: 105
url: /pl/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) metoda

Odszyfrowuje wiadomość. Nie zaimplementowano.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) do odszyfrowania. |
| use_oaep | **bool** | Prawda, aby użyć wypełnienia OAEP, fałsz, aby użyć wypełnienia PKCS#1 v1.5. |

### Wartość zwracana

Tablica odszyfrowanych danych.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metoda

Odszyfrowuje dane wejściowe przy użyciu określonego trybu wypełniania.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tablica do odszyfrowania. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Tryb wypełniania. |

### Wartość zwracana

Odszyfrowane dane w formacie tablicy bajtów.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [RSACryptoServiceProvider](../)
* Klasa [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)