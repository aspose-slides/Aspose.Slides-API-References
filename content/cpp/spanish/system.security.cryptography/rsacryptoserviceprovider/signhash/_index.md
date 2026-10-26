---
title: SignHash()
second_title: Referencia de API de Aspose.Slides para C++
description: Calcula la firma para el valor hash especificado.
type: docs
weight: 196
url: /es/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) método

Calcula la firma para el valor hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de relleno. devuelve [RSA](../../rsa/) firma para el hash especificado. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) método

Calcula la firma del valor de entrada especificado. No implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valor hash de los datos a firmar. |
| str | const [String](../../../system/string/)\& | Identificador del algoritmo hash usado para crear el hash. |

### Valor de retorno

[RSA](../../rsa/) firma para los datos especificados.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RSASignaturePadding](../../rsasignaturepadding/)
* Clase [RSACryptoServiceProvider](../)
* Clase [String](../../../system/string/)
* Estructura [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)