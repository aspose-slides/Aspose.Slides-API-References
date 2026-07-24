---
title: X509KeyStorageFlags
second_title: Aspose.Slides für C++ API Referenz
description: Definiert, wie der Schlüssel gespeichert wird.
type: docs
weight: 261
url: /de/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags Enum


Definiert, wie der Schlüssel gespeichert wird.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| DefaultKeySet | 0 | Standard-Schlüsselsatz verwenden. |
| UserKeySet | 1 | Benutzerbezogenen Speicher anstelle des maschinenlokalen verwenden. |
| MachineKeySet | 2 | Lokalen Maschinen-Speicher anstelle des Benutzerspeichers verwenden. |
| Exportable | 4 | Markiert importierte Schlüssel als exportierbar. |
| UserProtected | 8 | Benutzer benachrichtigen, dass der Schlüssel verwendet wird. |
| PersistKeySet | 16 | Der Schlüssel wird beim Importieren des Zertifikats gespeichert. |

## Siehe auch

* Namensraum [System::Security::Cryptography::X509Certificates](../)
* Bibliothek [Aspose.Slides](../../)