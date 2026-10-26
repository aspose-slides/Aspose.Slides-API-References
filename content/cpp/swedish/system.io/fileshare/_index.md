---
title: FileShare
second_title: Aspose.Slides för C++ API-referens
description: Anger vilken typ av åtkomst andra FileStream-objekt kan ha till en fil som öppnas.
type: docs
weight: 534
url: /sv/system.io/fileshare/
---
## FileShare enum

Anger vilken typ av åtkomst andra [FileStream](../filestream/) objekt kan ha till en fil som öppnas.

```cpp
enum class FileShare
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Ingen åtkomst. |
| Read | 1 | Endast läsåtkomst. |
| Write | 2 | Endast skrivaråtkomst. |
| ReadWrite | 3 | Läsa- och skrivaråtkomst. |
| Delete | 4 | Filen kan tas bort. |
| Inheritable | 16 | Gör filhandtaget ärftligt för barnprocesser. |

## Se även

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)