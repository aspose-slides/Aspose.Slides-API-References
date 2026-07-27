---
title: VerifyHash()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba la firma de los datos.
type: docs
weight: 118
url: /es/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) method


Comprueba la firma de los datos.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash calculado para los datos recibidos. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Firma tal como se recibió. |

### Valor devuelto

True si la firma es válida, false en caso contrario.

## Véase también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [ECDsa](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)