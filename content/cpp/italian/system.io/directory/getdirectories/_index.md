---
title: GetDirectories()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory indicata sia nell'intero albero di directory radicato nella directory specificata.
type: docs
weight: 66
url: /it/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String&, const String&, SearchOption) metodo


Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory indicata sia nell'intero albero di directory radicato nella directory specificata.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Percorso completo o relativo della directory in cui effettuare la ricerca |
| searchPattern | const [String](../../../system/string/)& | Modello di nome delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory indicata o nell'intero albero di directory radicato nella directory specificata |

### Valore di ritorno

Un array di percorsi completi delle directory trovate i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)