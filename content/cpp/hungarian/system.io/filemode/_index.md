---
title: FileMode
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogyan kell megnyitni egy fájlt.
type: docs
weight: 508
url: /hu/system.io/filemode/
---
## FileMode enum

Megadja, hogyan kell megnyitni egy fájlt.

```cpp
enum class FileMode
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| CreateNew | 1 | Új fájlt hoz létre. Ha a fájl már létezik, kivétel keletkezik. |
| Create | 2 | Új fájlt hoz létre. Ha a fájl már létezik, felülíródik. |
| Open | 3 | Megnyit egy meglévő fájlt. Ha a fájl nem létezik, kivétel keletkezik. |
| OpenOrCreate | 4 | Megnyit egy meglévő fájlt, vagy új fájlt hoz létre, ha nem létezik. |
| Truncate | 5 | Megnyit egy meglévő fájlt, és lerövidíti, hogy üres legyen. Ha a fájl nem létezik, kivétel keletkezik. |
| Append | 6 | Megnyit egy meglévő fájlt, és a végére pozícionálja, vagy új fájlt hoz létre, ha nem létezik. |

## Lásd még

* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)