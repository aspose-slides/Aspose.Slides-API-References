---
title: EnumerateDirectories()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata che nell'intero albero di directory radicato nella directory specificata.
type: docs
weight: 27
url: /it/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) method


Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata che nell'intero albero di directory radicato nella directory specificata.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Percorso completo o relativo della directory in cui eseguire la ricerca |
| searchPattern | const [String](../../../system/string/)\& | Il modello del nome delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory specificata o nell'intero albero di directory radicato nella directory specificata |

### Valore di ritorno

La collezione enumerabile dei percorsi completi delle directory trovate i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)