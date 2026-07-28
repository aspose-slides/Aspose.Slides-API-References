---
title: X509KeyStorageFlags
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogyan tárolódik a kulcs.
type: docs
weight: 261
url: /hu/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum

Meghatározza, hogyan tárolódik a kulcs.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| DefaultKeySet | 0 | Alapértelmezett kulcskészlet használata. |
| UserKeySet | 1 | Felhasználóhoz társított tároló használata a géphez tartozó helyi tároló helyett. |
| MachineKeySet | 2 | Helyi géptároló használata a felhasználói tároló helyett. |
| Exportable | 4 | Az importált kulcsok exportálhatóként történő jelölése. |
| UserProtected | 8 | Értesíti a felhasználót, hogy a kulcs használatban van. |
| PersistKeySet | 16 | A kulcs megmarad a tanúsítvány importálásakor. |

## Lásd még

* Névtér [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)