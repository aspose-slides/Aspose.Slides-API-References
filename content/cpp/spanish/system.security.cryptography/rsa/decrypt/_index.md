---
title: Decrypt()
second_title: Referencia de la API de Aspose.Slides para C++
description: Descifra los datos de entrada usando el modo de relleno especificado.
type: docs
weight: 27
url: /es/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) método

Descifra los datos de entrada utilizando el modo de relleno especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) matriz para descifrar. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Modo de relleno. |

### Valor devuelto

Datos descifrados en formato de matriz de bytes.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Clase [RSA](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)