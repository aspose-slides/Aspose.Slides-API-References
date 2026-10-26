---
title: TryFromOid()
second_title: Referencia de la API de Aspose.Slides para C++
description: Intente crear HashAlgorithmName a partir del valor OID.
type: docs
weight: 66
url: /es/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String&, HashAlgorithmName&) método

Intente crear [HashAlgorithmName](../) a partir del valor OID.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | Valor OID. |
| value | [HashAlgorithmName](../)\& | Salida [HashAlgorithmName](../). |

### Valor devuelto

true si el OID especificado es un algoritmo de hash válido, de lo contrario - false.

## Ver también

* Clase [String](../../../system/string/)
* Estructura [HashAlgorithmName](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)