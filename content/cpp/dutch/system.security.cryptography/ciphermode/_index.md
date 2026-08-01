---
title: CipherMode
second_title: Aspose.Slides voor C++ API-referentie
description: Blokcijfermodus.
type: docs
weight: 885
url: /nl/system.security.cryptography/ciphermode/
---
## CipherMode enum

Blokcijfermodus.

```cpp
enum class CipherMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining die het huidige blok combineert met het vorige blok om versleuteling te verbeteren. |
| ECB | 2 | Electronic codebook-modus zonder inter-block invloeden; resulteert in zwakkere versleuteling. |
| OFB | 3 | Output feedback-modus die grote invoerblokken in kleine stukjes verwerkt. |
| CFB | 4 | Cipher feedback-modus die grote invoerblokken in kleine stukjes verwerkt. Mangling-regels verschillen van die van OFB. |
| CTS | 5 | Cipher text stealing-modus, gedraagt zich als CBC voor alle behalve de twee laatste blokken van de tekst. |

## Zie ook

* Naamruimte [System::Security::Cryptography](../)
* Bibliotheek [Aspose.Slides](../../)