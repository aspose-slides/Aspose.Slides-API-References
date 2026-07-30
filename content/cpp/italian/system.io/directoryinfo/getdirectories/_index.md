---
title: GetDirectories()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un array contenente puntatori condivisi a oggetti DirectoryInfo che rappresentano tutte le directory situate nella directory rappresentata dall'oggetto corrente.
type: docs
weight: 144
url: /it/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() metodo


Restituisce un array contenente puntatori condivisi a oggetti [DirectoryInfo](../) che rappresentano tutte le directory situate nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) metodo


Cerca le directory che soddisfano i criteri di ricerca specificati nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome delle directory da cercare |

### Valore di ritorno

Un array di puntatori condivisi a oggetti [DirectoryInfo](../) che rappresentano le directory trovate i cui nomi corrispondono a **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) metodo


Cerca le directory che soddisfano i criteri di ricerca specificati sia nella directory rappresentata dall'oggetto corrente sia nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory rappresentata dall'oggetto corrente o nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente |

### Valore di ritorno

Un array di puntatori condivisi a oggetti [DirectoryInfo](../) che rappresentano le directory trovate i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)