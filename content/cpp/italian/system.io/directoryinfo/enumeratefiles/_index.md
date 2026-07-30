---
title: EnumerateFiles()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una collezione enumerabile contenente tutti i file situati nella directory rappresentata dall'oggetto corrente.
type: docs
weight: 118
url: /it/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metodo

Restituisce una collezione enumerabile contenente tutti i file situati nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) metodo

Cerca i file che soddisfano i criteri di ricerca specificati nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello del nome dei file da cercare |

### Valore di ritorno

La collezione enumerabile di puntatori condivisi a oggetti [FileInfo](../../fileinfo/) che rappresentano i file trovati i cui nomi corrispondono a **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metodo

Cerca i file che soddisfano i criteri di ricerca specificati sia nella directory rappresentata dall'oggetto corrente sia nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello del nome dei file da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory rappresentata dall'oggetto corrente o nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente |

### Valore di ritorno

La collezione enumerabile di puntatori condivisi a oggetti [FileInfo](../../fileinfo/) che rappresentano i file trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)