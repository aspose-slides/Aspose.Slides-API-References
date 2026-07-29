---
title: CipherMode
second_title: Aspose.Slides för C++ API-referens
description: Blockkrypteringsläge.
type: docs
weight: 885
url: /sv/system.security.cryptography/ciphermode/
---
## CipherMode enum

Block cipher mode.

```cpp
enum class CipherMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining som kombinerar aktuellt block med föregående block för att förbättra krypteringen. |
| ECB | 2 | Electronic codebook-läge utan inter-block-inverkan; resulterar i svagare kryptering. |
| OFB | 3 | Output feedback-läge som hanterar stora inmatningsblock i små delar. |
| CFB | 4 | Cipher feedback-läge som hanterar stora inmatningsblock i små delar. Manglingsreglerna skiljer sig från dem i OFB. |
| CTS | 5 | Cipher text stealing-läge, beter sig som CBC för alla förutom de två sista blocken av text. |

## Se även

* Namnrymd [System::Security::Cryptography](../)
* Bibliotek [Aspose.Slides](../../)