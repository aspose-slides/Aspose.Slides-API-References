---
title: Decrypt()
second_title: Referência da API Aspose.Slides para C++
description: Descriptografa os dados de entrada usando o modo de preenchimento especificado.
type: docs
weight: 27
url: /pt/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) método

Descriptografa os dados de entrada usando o modo de preenchimento especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array a ser descriptografado. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modo de preenchimento. |

### Valor de Retorno

Dados descriptografados no formato de array de bytes.

## Ver também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Classe [RSA](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)