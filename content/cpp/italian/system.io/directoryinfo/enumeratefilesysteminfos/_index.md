---
title: EnumerateFileSystemInfos()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce una collezione enumerabile contenente tutti i file e le directory situati nella directory rappresentata dall'oggetto corrente.
type: docs
weight: 131
url: /it/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metodo


Restituisce una collezione enumerabile contenente tutti i file e le directory situati nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metodo


Cerca i file e le directory che soddisfano i criteri di ricerca specificati nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome dei file e delle directory da cercare |

### Valore restituito

La collezione enumerabile di puntatori condivisi a oggetti [FileSystemInfo](../../filesysteminfo/) che rappresentano i file e le directory trovati i cui nomi corrispondono a **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metodo


Cerca i file e le directory che soddisfano i criteri di ricerca specificati sia nella directory rappresentata dall'oggetto corrente sia nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome dei file e delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory rappresentata dall'oggetto corrente o nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente |

### Valore restituito

La collezione enumerabile di puntatori condivisi a oggetti [FileSystemInfo](../../filesysteminfo/) che rappresentano i file e le directory trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)