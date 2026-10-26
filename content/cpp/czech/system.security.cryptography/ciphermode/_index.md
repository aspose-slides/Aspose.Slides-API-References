---
title: CipherMode
second_title: Aspose.Slides pro C++ API Reference
description: Blokový režim šifry.
type: docs
weight: 885
url: /cs/system.security.cryptography/ciphermode/
---
## CipherMode enum

Blokový režim šifry.

```cpp
enum class CipherMode
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| CBC | 1 | Řetězení bloků šifry, které kombinuje aktuální blok s předchozím blokem pro zlepšení šifrování. |
| ECB | 2 | Režim elektronické knihy kódů bez vzájemných vlivů mezi bloky; vede k slabšímu šifrování. |
| OFB | 3 | Režim výstupní zpětné vazby, který zpracovává velké vstupní bloky po malých částech. |
| CFB | 4 | Režim zpětné vazby šifry, který zpracovává velké vstupní bloky po malých částech. Pravidla míchání se liší od těch v OFB. |
| CTS | 5 | Režim odcizení šifrového textu, který se chová jako CBC pro všechny bloky kromě posledních dvou bloků textu. |

## Viz také

* jmenný prostor [System::Security::Cryptography](../)
* Knihovna [Aspose.Slides](../../)