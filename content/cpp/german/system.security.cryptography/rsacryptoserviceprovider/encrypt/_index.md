---
title: Encrypt()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschlüsselt die Nachricht. Nicht implementiert.
type: docs
weight: 118
url: /de/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) Methode

Verschlüsselt die Nachricht. Nicht implementiert.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) zum Verschlüsseln. |
| use_oaep | **bool** | True, um OAEP-Padding zu verwenden, false, um PKCS#1 v1.5-Padding zu verwenden. |

### Rückgabewert

Verschlüsseltes Datenarray.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) Methode

Verschlüsselt Eingabedaten mit dem angegebenen Padding-Modus.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) Array zum Verschlüsseln. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding-Modus. |

### Rückgabewert

Verschlüsselte Daten im Byte-Array-Format.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)