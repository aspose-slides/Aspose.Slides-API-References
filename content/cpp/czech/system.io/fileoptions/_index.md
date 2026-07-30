---
title: FileOptions
second_title: Aspose.Slides pro referenci API C++
description: Reprezentuje pokročilé možnosti pro vytvoření objektu FileStream.
type: docs
weight: 521
url: /cs/system.io/fileoptions/
---
## FileOptions enum

Reprezentuje pokročilé možnosti pro vytvoření objektu [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Žádné další možnosti. |
| Encrypted | 16384 | Soubor je šifrován. NOT IMPLEMENTED. |
| DeleteOnClose | 67108864 | Soubor by měl být automaticky smazán, když už není používán. |
| SequentialScan | 134217728 | Soubor by měl být přístupován sekvenčně. |
| RandomAccess | 268435456 | Soubor je přístupován náhodně. |
| Asynchronous | 1073741824 | Soubor může být použit pro asynchronní I/O operace. |
| WriteThrough | n/a | Všechny zápisy by měly jít přímo na disk, obcházejíce jakoukoli mezipaměť. |

## Viz také

* jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)