---
title: GetFileSystemInfos()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array contenente puntatori condivisi a oggetti FileSystemInfo che rappresentano tutti i file e le directory situati nella directory rappresentata dall'oggetto corrente.
type: docs
weight: 170
url: /it/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() metodo


Restituisce un array contenente puntatori condivisi a oggetti [FileSystemInfo](../../filesysteminfo/) che rappresentano tutti i file e le directory situati nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) metodo


Cerca i file e le directory che soddisfano i criteri di ricerca specificati nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello del nome dei file e delle directory da cercare |

### Valore di ritorno

Un array di puntatori condivisi a oggetti [FileSystemInfo](../../filesysteminfo/) che rappresentano i file e le directory trovati i cui nomi corrispondono a **searchPattern**


## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) metodo


Cerca i file e le directory che soddisfano i criteri di ricerca specificati sia nella directory rappresentata dall'oggetto corrente sia nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello del nome dei file e delle directory da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory rappresentata dall'oggetto corrente o nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente |

### Valore di ritorno

Un array di puntatori condivisi a oggetti [FileSystemInfo](../../filesysteminfo/) che rappresentano i file e le directory trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)