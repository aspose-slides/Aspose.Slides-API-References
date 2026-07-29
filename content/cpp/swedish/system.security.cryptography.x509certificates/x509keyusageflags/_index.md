---
title: X509KeyUsageFlags
second_title: Aspose.Slides för C++ API-referens
description: Definierar hur certifikatnyckeln kan användas.
type: docs
weight: 274
url: /sv/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum


Definierar hur certifikatnyckeln kan användas.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Inga nyckelanvändningsparametrar. |
| EncipherOnly | 1 | Nyckeln kan endast användas för kryptering. |
| CrlSign | 2 | Nyckeln kan användas för att signera en certifikatåterkallelse-lista. |
| KeyCertSign | 4 | Nyckeln kan användas för att signera certifikat. |
| KeyAgreement | 8 | Nyckeln kan användas för att fastställa nyckelavtal. |
| DataEncipherment | 16 | Nyckeln kan användas för datakryptering. |
| KeyEncipherment | 32 | Nyckeln kan användas för nyckelkryptering. |
| NonRepudiation | 64 | Nyckeln kan användas för autentisering. |
| DigitalSignature | 128 | Nyckeln kan användas som en digital signatur. |
| DecipherOnly | 32768 | Nyckeln kan endast användas för dekryptering. |

## Se också

* Namnrymd [System::Security::Cryptography::X509Certificates](../)
* Bibliotek [Aspose.Slides](../../)