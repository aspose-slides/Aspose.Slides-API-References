---
title: EnumerateFileSystemEntries()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca i file e le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero delle directory radicato nella directory specificata.
type: docs
weight: 53
url: /it/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) metodo

Cerca i file e le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero delle directory radicato nella directory specificata.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Percorso completo o relativo della directory in cui cercare |
| searchPattern | const [String](../../../system/string/)\& | Modello del nome dei file e delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory specificata o nell'intero albero delle directory radicato nella directory specificata |

### Valore restituito

La collezione enumerabile dei percorsi completi dei file e delle directory trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)