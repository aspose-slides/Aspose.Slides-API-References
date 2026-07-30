---
title: Encrypt()
second_title: Riferimento API di Aspose.Slides per C++
description: Cifra i dati di input usando la modalità di padding specificata.
type: docs
weight: 53
url: /it/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metodo

Cifra i dati di input usando la modalità di padding specificata.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array da cifrare. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modalità di padding. |

### Valore di ritorno

Dati crittati in formato array di byte.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Classe [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)