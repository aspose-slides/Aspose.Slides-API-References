---
title: Decrypt()
second_title: Referencia de API de Aspose.Slides para C++
description: Descifra el mensaje. No implementado.
type: docs
weight: 105
url: /es/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) método


Descifra el mensaje. No implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) para descifrar. |
| use_oaep | **bool** | True para usar padding OAEP, false para usar padding PKCS#1 v1.5. |

### Valor de retorno

Matriz de datos descifrados.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) método


Descifra los datos de entrada usando el modo de padding especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array para descifrar. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modo de padding. |

### Valor de retorno

Datos descifrados en formato de array de bytes.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)