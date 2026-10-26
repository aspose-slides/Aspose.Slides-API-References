---
title: CipherMode
second_title: Riferimento API di Aspose.Slides per C++
description: Modalità di cifratura a blocchi.
type: docs
weight: 885
url: /it/system.security.cryptography/ciphermode/
---
## CipherMode enum


Modalità di cifratura a blocchi.

```cpp
enum class CipherMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| CBC | 1 | Catena di blocchi di cifratura che combina il blocco corrente con il blocco precedente per migliorare la cifratura. |
| ECB | 2 | Modalità Electronic codebook senza influenze tra blocchi; produce una cifratura più debole. |
| OFB | 3 | Modalità Output feedback che gestisce grandi blocchi di input in piccoli pezzi. |
| CFB | 4 | Modalità Cipher feedback che gestisce grandi blocchi di input in piccoli pezzi. Le regole di manipolazione differiscono da quelle di OFB. |
| CTS | 5 | Modalità Cipher text stealing, si comporta come CBC per tutti i blocchi di testo eccetto gli ultimi due. |

## Vedi anche

* Namespace [System::Security::Cryptography](../)
* Libreria [Aspose.Slides](../../)