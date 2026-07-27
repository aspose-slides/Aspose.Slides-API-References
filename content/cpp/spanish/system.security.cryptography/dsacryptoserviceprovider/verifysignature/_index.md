---
title: VerifySignature()
second_title: Referencia de la API de Aspose.Slides para C++
description: Verifica la firma DSA para los datos especificados.
type: docs
weight: 118
url: /es/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) método


Verifica la firma [DSA](../../dsa/) para los datos especificados.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) firmado con **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) firma. |

### Valor de retorno

true - si **rgb_signature** coincide con la firma [DSA](../../dsa/) calculada sobre **rgb_hash**, de lo contrario - false.

## Véase también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [DSACryptoServiceProvider](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)