---
title: EnumerateFiles()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca i file che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata.
type: docs
weight: 40
url: /it/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) metodo

Cerca i file che soddisfano i criteri di ricerca specificati, sia nella directory specificata sia nell'intero albero di directory radicato nella directory specificata.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Percorso completo o relativo della directory in cui cercare |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome dei file da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory specificata o nell'intero albero di directory radicato nella directory specificata |

### Valore di ritorno

La collezione enumerabile dei percorsi completi dei file trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)