---
title: Decrypt()
second_title: Aspose.Slides for C++ API Referenciája
description: Dekódolja az üzenetet. Nincs megvalósítva.
type: docs
weight: 105
url: /hu/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Dekódolja az üzenetet. Nincs megvalósítva.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) a dekódoláshoz. |
| use_oaep | **bool** | True, ha OAEP kitöltést használ, false, ha PKCS#1 v1.5 kitöltést használ. |

### Visszatérési érték

Dekódolt adat tömb.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Dekódolja a bemeneti adatot a megadott kitöltési mód segítségével.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tömb a dekódoláshoz. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Kitöltési mód. |

### Visszatérési érték

Dekódolt adat byte tömb formátumban.

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [RSACryptoServiceProvider](../)
* Osztály [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)