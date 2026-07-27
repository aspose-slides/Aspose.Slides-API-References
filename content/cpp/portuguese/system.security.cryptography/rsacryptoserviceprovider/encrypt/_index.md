---
title: Encrypt()
second_title: Aspose.Slides para C++ Referência da API
description: Criptografa a mensagem. Não implementado.
type: docs
weight: 118
url: /pt/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method

Criptografa a mensagem. Não implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) para criptografar. |
| use_oaep | **bool** | True para usar preenchimento OAEP, false para usar preenchimento PKCS#1 v1.5. |

### Return Value

Encrypted data array.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

Criptografa os dados de entrada usando o modo de preenchimento especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array para criptografar. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modo de preenchimento. |

### Return Value

Encrypted data in byte array format.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)