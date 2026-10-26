---
title: VerifySignature()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifique la firma DSA para los datos especificados.
type: docs
weight: 14
url: /es/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) método


Verifica la firma [DSA](../) para los datos especificados.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) firmada con **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) firma. |

### Valor de retorno

true - si **rgb_signature** coincide con la firma [DSA](../) calculada sobre **rgb_hash**, de lo contrario - false.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [DSA](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)