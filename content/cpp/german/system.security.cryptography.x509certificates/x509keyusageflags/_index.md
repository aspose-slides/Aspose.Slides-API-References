---
title: X509KeyUsageFlags
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert, wie der Zertifikatschlüssel verwendet werden kann.
type: docs
weight: 274
url: /de/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Definiert, wie der Zertifikatschlüssel verwendet werden kann.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Keine Schlüsselverwendungsparameter. |
| EncipherOnly | 1 | Schlüssel kann nur für die Verschlüsselung verwendet werden. |
| CrlSign | 2 | Schlüssel kann verwendet werden, um eine Zertifikatswiderrufsliste zu signieren. |
| KeyCertSign | 4 | Schlüssel kann zum Signieren von Zertifikaten verwendet werden. |
| KeyAgreement | 8 | Schlüssel kann zur Schlüsselaushandlung verwendet werden. |
| DataEncipherment | 16 | Schlüssel kann für die Datenverschlüsselung verwendet werden. |
| KeyEncipherment | 32 | Schlüssel kann für die Schlüsselverschlüsselung verwendet werden. |
| NonRepudiation | 64 | Schlüssel kann zur Authentifizierung verwendet werden. |
| DigitalSignature | 128 | Schlüssel kann als digitale Signatur verwendet werden. |
| DecipherOnly | 32768 | Schlüssel kann nur für die Entschlüsselung verwendet werden. |

## Siehe auch

* Namensraum [System::Security::Cryptography::X509Certificates](../)
* Bibliothek [Aspose.Slides](../../)