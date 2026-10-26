---
title: TryFromOid()
second_title: Aspose.Slides C++ API referencia
description: Megpróbálja létrehozni a HashAlgorithmName-t OID-értékből.
type: docs
weight: 66
url: /hu/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) method


Próbálja meg létrehozni [HashAlgorithmName](../) az OID-értékből.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID érték. |
| value | [HashAlgorithmName](../)\& | Kimenet [HashAlgorithmName](../). |

### Visszatérési érték

true, ha a megadott OID érvényes hash algoritmus, egyébként - false.

## Lásd még

* Osztály [String](../../../system/string/)
* Struktúra [HashAlgorithmName](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)