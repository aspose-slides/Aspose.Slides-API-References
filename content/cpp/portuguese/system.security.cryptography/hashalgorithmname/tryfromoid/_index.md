---
title: TryFromOid()
second_title: Referência da API Aspose.Slides para C++
description: Tente criar HashAlgorithmName a partir do valor OID.
type: docs
weight: 66
url: /pt/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) método

Tente criar [HashAlgorithmName](../) a partir do valor OID.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | Valor OID. |
| value | [HashAlgorithmName](../)\& | Saída [HashAlgorithmName](../). |

### Valor de retorno

true se o OID especificado for um algoritmo de hash válido, caso contrário - false.

## Veja também

* Classe [String](../../../system/string/)
* Estrutura [HashAlgorithmName](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)