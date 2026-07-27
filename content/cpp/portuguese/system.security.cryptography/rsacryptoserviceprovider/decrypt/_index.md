---
title: Decrypt()
second_title: Referência de API Aspose.Slides para C++
description: Descriptografa a mensagem. Não implementado.
type: docs
weight: 105
url: /pt/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method

Descriptografa mensagem. Não implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) para descriptografar. |
| use_oaep | **bool** | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### Valor de Retorno

Decrypted data array.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

Descriptografa os dados de entrada usando o modo de preenchimento especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array para descriptografar. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding mode. |

### Valor de Retorno

Decrypted data in byte array format.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSACryptoServiceProvider](../)
* Classe [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)