---
title: VerifyHash()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica la firma de los datos.
type: docs
weight: 222
url: /es/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) método

Verifica la firma de los datos.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calculado para los datos recibidos. |
| str | const [String](../../../system/string/)\& | Nombre del algoritmo de hash utilizado. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Firma recibida. |

### Return Value

True si la firma es válida, false en caso contrario.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [String](../../../system/string/)
* Clase [DSACryptoServiceProvider](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)