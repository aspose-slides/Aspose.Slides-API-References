---
title: FileOptions
second_title: Aspose.Slides för C++ API-referens
description: Representerar avancerade alternativ för att skapa FileStream-objekt.
type: docs
weight: 521
url: /sv/system.io/fileoptions/
---
## FileOptions-enum

Representerar avancerade alternativ för att skapa [FileStream](../filestream/) objekt.

```cpp
enum class FileOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Inga ytterligare alternativ. |
| Encrypted | 16384 | Filen är krypterad. INTE IMPLEMENTERAD. |
| DeleteOnClose | 67108864 | Filen ska automatiskt raderas när den inte längre används. |
| SequentialScan | 134217728 | Filen bör nås sekventiellt. |
| RandomAccess | 268435456 | Filen nås slumpmässigt. |
| Asynchronous | 1073741824 | Filen kan användas för asynkrona I/O-operationer. |
| WriteThrough | n/a | Alla skrivningar ska gå direkt till disken utan någon mellanliggande cache. |

## Se även

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)