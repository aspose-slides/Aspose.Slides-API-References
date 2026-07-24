---
title: CipherMode
second_title: Aspose.Slides für C++ API Referenz
description: Blockcipher-Modus.
type: docs
weight: 885
url: /de/system.security.cryptography/ciphermode/
---
## CipherMode enum

Blockcipher-Modus.

```cpp
enum class CipherMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining, das den aktuellen Block mit dem vorherigen Block kombiniert, um die Verschlüsselung zu verbessern. |
| ECB | 2 | Electronic codebook mode ohne Einfluss zwischen Blöcken; führt zu schwächerer Verschlüsselung. |
| OFB | 3 | Output-feedback-Modus, der große Eingabeblöcke in kleinen Teilen verarbeitet. |
| CFB | 4 | Cipher-feedback-Modus, der große Eingabeblöcke in kleinen Teilen verarbeitet. Die Mangling-Regeln unterscheiden sich von denen des OFB. |
| CTS | 5 | Cipher-text-stealing-Modus, der sich wie CBC verhält, außer bei den letzten beiden Blöcken des Textes. |

## Siehe auch

* Namensraum [System::Security::Cryptography](../)
* Bibliothek [Aspose.Slides](../../)