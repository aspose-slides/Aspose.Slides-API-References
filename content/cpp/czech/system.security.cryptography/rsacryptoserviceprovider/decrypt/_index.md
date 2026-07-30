---
title: Decrypt()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Dešifruje zprávu. Není implementováno.
type: docs
weight: 105
url: /cs/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) metoda

Dešifruje zprávu. Není implementováno.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) k dešifrování. |
| use_oaep | **bool** | True pro použití OAEP paddingu, false pro použití paddingu PKCS#1 v1.5. |

### Návratová hodnota

Pole dešifrovaných dat.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metoda

Dešifruje vstupní data pomocí určeného režimu paddingu.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) pole k dešifrování. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Režim paddingu. |

### Návratová hodnota

Dešifrovaná data ve formátu pole bytů.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSACryptoServiceProvider](../)
* Třída [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)