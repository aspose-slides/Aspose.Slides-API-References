---
title: Encrypt()
second_title: Riferimento API di Aspose.Slides per C++
description: Cifra il messaggio. Non implementato.
type: docs
weight: 118
url: /it/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) metodo

Cifra il messaggio. Non implementato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) da cifrare. |
| use_oaep | **bool** | True per usare il padding OAEP, false per usare il padding PKCS#1 v1.5. |

### Valore restituito

Array di dati cifrati.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metodo

Cifra i dati di input usando la modalità di padding specificata.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array da cifrare. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modalità di padding. |

### Valore restituito

Dati cifrati in formato array di byte.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSACryptoServiceProvider](../)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)