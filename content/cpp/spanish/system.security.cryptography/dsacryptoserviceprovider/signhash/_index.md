---
title: SignHash()
second_title: Referencia de API de Aspose.Slides para C++
description: Calcula la firma del valor de entrada especificado.
type: docs
weight: 196
url: /es/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) método

Calcula la firma del valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valor hash de los datos a firmar. |
| str | const [String](../../../system/string/)\& | Identificador del algoritmo hash usado para crear el hash. |

## Valor devuelto

[DSA](../../dsa/) firma para los datos especificados.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [String](../../../system/string/)
* Clase [DSACryptoServiceProvider](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)