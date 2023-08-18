---
title: TryFromOid()
second_title: Aspose.Slides for C++ API Reference
description: Try to create HashAlgorithmName from OID-value.
type: docs
weight: 66
url: /system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) method


Try to create [HashAlgorithmName](../) from OID-value.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID value. |
| value | [HashAlgorithmName](../)\& | Output [HashAlgorithmName](../). |

### Return Value

true if specified OID is a valid hash algorithm, otherwise - false.

## See Also

* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)