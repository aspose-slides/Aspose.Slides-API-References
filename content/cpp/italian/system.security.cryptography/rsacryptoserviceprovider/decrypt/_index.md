---
title: Decrypt()
second_title: Riferimento API di Aspose.Slides per C++
description: Decrittografa il messaggio. Non implementato.
type: docs
weight: 105
url: /it/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method

Decrittografa il messaggio. Non implementato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) da decrittografare. |
| use_oaep | **bool** | True per utilizzare il padding OAEP, false per utilizzare il padding PKCS#1 v1.5. |

### Valore di ritorno

Array di dati decrittografati.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

Decrittografa i dati di input usando la modalità di padding specificata.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array da decrittografare. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modalità di padding. |

### Valore di ritorno

Dati decrittografati in formato array di byte.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSACryptoServiceProvider](../)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)