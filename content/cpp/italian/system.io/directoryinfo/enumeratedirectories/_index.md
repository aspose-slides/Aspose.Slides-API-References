---
title: EnumerateDirectories()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce una collezione enumerabile contenente tutte le directory situate nella directory rappresentata dall'oggetto corrente.
type: docs
weight: 105
url: /it/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metodo

Restituisce una collezione enumerabile contenente tutte le directory situate nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metodo

Cerca le directory che soddisfano i criteri di ricerca specificati nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome delle directory da cercare |

### Valore restituito

La collezione enumerabile di puntatori condivisi a oggetti [DirectoryInfo](../) che rappresentano le directory trovate i cui nomi corrispondono a **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metodo

Cerca le directory che soddisfano i criteri di ricerca specificati, sia nella directory rappresentata dall'oggetto corrente sia nell'intero albero delle directory radicato nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory rappresentata dall'oggetto corrente o nell'intero albero delle directory radicato nella directory rappresentata dall'oggetto corrente |

### Valore restituito

La collezione enumerabile di puntatori condivisi a oggetti [DirectoryInfo](../) che rappresentano le directory trovate i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [DirectoryInfo](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)