---
title: TryFromOid()
second_title: Aspose.Slides for C++ API संदर्भ
description: OID-मान से HashAlgorithmName बनाने का प्रयत्न करें।
type: docs
weight: 66
url: /hi/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) विधि

OID-मूल्य से [HashAlgorithmName](../) बनाने का प्रयत्न करें।

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID value. |
| value | [HashAlgorithmName](../)\& | Output [HashAlgorithmName](../). |

### वापसी मान

true if specified OID is a valid hash algorithm, otherwise - false.

## संबंधित देखें

* क्लास [String](../../../system/string/)
* स्ट्रक्ट [HashAlgorithmName](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)