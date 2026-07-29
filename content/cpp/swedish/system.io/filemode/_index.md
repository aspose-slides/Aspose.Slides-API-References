---
title: FileMode
second_title: Aspose.Slides för C++ API-referens
description: Anger hur en fil ska öppnas.
type: docs
weight: 508
url: /sv/system.io/filemode/
---
## FileMode enum

Anger hur en fil ska öppnas.

```cpp
enum class FileMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| CreateNew | 1 | Skapa en ny fil. Om filen redan finns, kastas ett undantag. |
| Create | 2 | Skapa en ny fil. Om filen redan finns, skrivs den över. |
| Open | 3 | Öppna en befintlig fil. Om filen inte finns, kastas ett undantag. |
| OpenOrCreate | 4 | Öppna en befintlig fil eller skapa en ny om den inte finns. |
| Truncate | 5 | Öppna en befintlig fil och trunkera den så att den blir tom. Om filen inte finns, kastas ett undantag. |
| Append | 6 | Öppna en befintlig fil och sök till slutet av den eller skapa en ny om den inte finns. |

## Se även

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)