---
title: X509KeyUsageFlags
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a tanúsítvány kulcs hogyan használható.
type: docs
weight: 274
url: /hu/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Meghatározza, hogy a tanúsítvány kulcs hogyan használható.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Nincs kulcshasználati paraméter. |
| EncipherOnly | 1 | A kulcs csak titkosításhoz használható. |
| CrlSign | 2 | A kulcs tanúsítvány visszavonási lista aláírására használható. |
| KeyCertSign | 4 | A kulcs tanúsítványok aláírására használható. |
| KeyAgreement | 8 | A kulcs kulcsmegállapodás meghatározására használható. |
| DataEncipherment | 16 | A kulcs adat titkosítására használható. |
| KeyEncipherment | 32 | A kulcs kulcs titkosítására használható. |
| NonRepudiation | 64 | A kulcs hitelesítésre használható. |
| DigitalSignature | 128 | A kulcs digitális aláírásként használható. |
| DecipherOnly | 32768 | A kulcs csak visszafejtésre használható. |

## Lásd még

* Névtér [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)