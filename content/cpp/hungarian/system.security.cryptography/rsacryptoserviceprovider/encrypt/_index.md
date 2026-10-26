---
title: Encrypt()
second_title: Aspose.Slides C++ API referencia
description: Titkosítja az üzenetet. Nincs megvalósítva.
type: docs
weight: 118
url: /hu/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) metódus

Titkosítja az üzenetet. Nincs megvalósítva.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) a titkosításhoz. |
| use_oaep | **bool** | True az OAEP kitöltés használatához, false a PKCS#1 v1.5 kitöltéshez. |

### Visszatérési érték

Titkosított adat tömb.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metódus

Titkosítja a bemeneti adatot a megadott kitöltési móddal.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tömb titkosításához. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Kitöltési mód. |

### Visszatérési érték

Titkosított adat bájt tömb formátumban.

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [RSACryptoServiceProvider](../)
* Osztály [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)