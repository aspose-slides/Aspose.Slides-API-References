---
title: Encrypt()
second_title: Aspose.Slides para C++ Referência da API
description: Criptografa os dados de entrada usando o modo de preenchimento especificado.
type: docs
weight: 53
url: /pt/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) método

Criptografa os dados de entrada usando o modo de preenchimento especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array a criptografar. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modo de preenchimento. |

### Valor de Retorno

Dados criptografados no formato de array de bytes.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Classe [RSA](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)