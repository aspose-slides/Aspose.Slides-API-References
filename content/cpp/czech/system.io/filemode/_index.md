---
title: FileMode
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, jak má být soubor otevřen.
type: docs
weight: 508
url: /cs/system.io/filemode/
---
## FileMode výčtový typ

Určuje, jak má být soubor otevřen.

```cpp
enum class FileMode
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| CreateNew | 1 | Create nový soubor. Pokud soubor již existuje, je vyvolána výjimka. |
| Create | 2 | Create nový soubor. Pokud soubor již existuje, je přepsán. |
| Open | 3 | Open existující soubor. Pokud soubor neexistuje, je vyvolána výjimka. |
| OpenOrCreate | 4 | Open existující soubor nebo vytvoří nový, pokud neexistuje. |
| Truncate | 5 | Truncate existující soubor a zkrátí jej na prázdný. Pokud soubor neexistuje, je vyvolána výjimka. |
| Append | 6 | Append existující soubor a přesune kurzor na jeho konec nebo vytvoří nový, pokud neexistuje. |

## Viz také

* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)