---
title: Encrypt()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cifra los datos de entrada utilizando el modo de relleno especificado.
type: docs
weight: 53
url: /es/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) método


Cifra los datos de entrada utilizando el modo de relleno especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array a cifrar. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modo de relleno. |

### Valor devuelto

Datos cifrados en formato de matriz de bytes.

## Véase también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Clase [RSA](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)