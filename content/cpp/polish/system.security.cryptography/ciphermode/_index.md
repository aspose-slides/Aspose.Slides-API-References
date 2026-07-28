---
title: CipherMode
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tryb szyfru blokowego.
type: docs
weight: 885
url: /pl/system.security.cryptography/ciphermode/
---
## CipherMode enumeracja

Tryb szyfru blokowego.

```cpp
enum class CipherMode
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| CBC | 1 | Łańcuchowanie bloków szyfru, które łączy bieżący blok z poprzednim, aby poprawić szyfrowanie. |
| ECB | 2 | Tryb elektronicznej książki kodów bez wpływu między blokami; skutkuje słabszym szyfrowaniem. |
| OFB | 3 | Tryb informacji zwrotnej wyjścia, który obsługuje duże bloki wejściowe w małych częściach. |
| CFB | 4 | Tryb informacji zwrotnej szyfru, który obsługuje duże bloki wejściowe w małych częściach. Reguły mieszania różnią się od tych w OFB. |
| CTS | 5 | Tryb kradzieży tekstu szyfru, zachowuje się jak CBC dla wszystkich bloków oprócz dwóch ostatnich bloków tekstu. |

## Zobacz także

* Przestrzeń nazw [System::Security::Cryptography](../)
* Biblioteka [Aspose.Slides](../../)