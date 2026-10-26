---
title: Decrypt()
second_title: Aspose.Slides für C++ API-Referenz
description: Entschlüsselt die Nachricht. Nicht implementiert.
type: docs
weight: 105
url: /de/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) Methode


Entschlüsselt die Nachricht. Nicht implementiert.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) zum Entschlüsseln. |
| use_oaep | **bool** | True, um OAEP-Padding zu verwenden, false, um PKCS#1 v1.5-Padding zu verwenden. |

### Rückgabewert

Entschlüsselte Datenarray.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) Methode


Entschlüsselt Eingabedaten mit dem angegebenen Padding-Modus.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) Array zum Entschlüsseln. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding-Modus. |

### Rückgabewert

Entschlüsselte Daten im Byte-Array-Format.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)