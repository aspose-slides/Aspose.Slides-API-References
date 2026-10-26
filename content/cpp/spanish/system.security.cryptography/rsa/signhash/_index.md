---
title: SignHash()
second_title: Referencia de la API de Aspose.Slides para C++
description: Calcula la firma para el valor de hash especificado.
type: docs
weight: 144
url: /es/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) método


Calcula la firma para el valor de hash especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor de hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de relleno. devuelve [RSA](../) firma para el hash especificado. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RSASignaturePadding](../../rsasignaturepadding/)
* Clase [RSA](../)
* Estructura [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)