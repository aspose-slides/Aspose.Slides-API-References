---
title: Encrypt()
second_title: Aspose.Slides pro C++ API Reference
description: Šifruje zprávu. Není implementováno.
type: docs
weight: 118
url: /cs/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Šifruje zprávu. Není implementováno.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) k šifrování. |
| use_oaep | **bool** | True pro použití OAEP vycpávky, false pro použití PKCS#1 v1.5 vycpávky. |

### Návratová hodnota

Šifrované pole dat.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Šifruje vstupní data pomocí zadaného režimu vycpávky.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) pole k šifrování. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Režim vycpávky. |

### Návratová hodnota

Šifrovaná data v podobě pole bytů.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSACryptoServiceProvider](../)
* Třída [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)