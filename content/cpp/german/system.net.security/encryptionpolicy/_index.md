---
title: EncryptionPolicy
second_title: Aspose.Slides für C++ API-Referenz
description: Enumeriert die Verschlüsselungsrichtlinien.
type: docs
weight: 53
url: /de/system.net.security/encryptionpolicy/
---
## EncryptionPolicy Enum

Enumeriert die Verschlüsselungsrichtlinien.

```cpp
enum class EncryptionPolicy
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| RequireEncryption | 0 | Erfordert Verschlüsselung und erlaubt niemals einen 'Null' Cipher. |
| AllowNoEncryption | 1 | Bevorzugt die Verwendung vollständiger Verschlüsselung, aber ein 'Null' Cipher kann verwendet werden, wenn der Server zustimmt. |
| NoEncryption | 2 | Erlaubt keine Verschlüsselung und fordert die Verwendung eines 'Null' Cipher, wenn das Gegenende einen 'Null' Cipher verarbeiten kann. |

## Siehe auch

* Namensraum [System::Net::Security](../)
* Bibliothek [Aspose.Slides](../../)