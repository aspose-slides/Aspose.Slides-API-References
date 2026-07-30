---
title: GetFileSystemEntries()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca i file e le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata.
type: docs
weight: 92
url: /it/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) metodo


Cerca i file e le directory che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Percorso completo o relativo della directory in cui eseguire la ricerca |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome dei file e delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory specificata o nell'intero albero di directory radicato nella directory specificata |

### Valore di ritorno

Un array di percorsi completi dei file e delle directory trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)