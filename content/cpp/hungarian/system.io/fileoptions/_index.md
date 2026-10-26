---
title: FileOptions
second_title: Aspose.Slides C++ API referencia
description: A FileStream objektum létrehozásához fejlett beállításokat képvisel.
type: docs
weight: 521
url: /hu/system.io/fileoptions/
---
## FileOptions enum

A [FileStream](../filestream/) objektum létrehozásához fejlett beállításokat képvisel.

```cpp
enum class FileOptions
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Nincsenek további beállítások. |
| Encrypted | 16384 | A fájl titkosított. NEM VALÓSÍTOTT. |
| DeleteOnClose | 67108864 | A fájlt automatikusan törölni kell, amikor már nincs használatban. |
| SequentialScan | 134217728 | A fájlt sorosan kell elérni. |
| RandomAccess | 268435456 | A fájl véletlenszerűen érhető el. |
| Asynchronous | 1073741824 | A fájlt aszinkron I/O műveletekre lehet használni. |
| WriteThrough | n/a | Minden írás közvetlenül a lemezre kell, hogy kerüljön, megkerülve minden köztes gyorsítótárat. |

## Lásd még

* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)