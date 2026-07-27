---
title: VerifyHash()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica que la firma del hash especificado sea válida.
type: docs
weight: 170
url: /es/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) método


Verifica que la firma del hash especificado sea válida.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor hash de los datos firmados. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Datos de la firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de relleno. devuelve true si la firma es válida, de lo contrario - false. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RSASignaturePadding](../../rsasignaturepadding/)
* Clase [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)