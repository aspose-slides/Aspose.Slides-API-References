---
title: GetFiles()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array contenente puntatori condivisi a oggetti FileInfo che rappresentano tutte le directory situate nella directory rappresentata dall'oggetto corrente.
type: docs
weight: 157
url: /it/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() metodo


Restituisce un array contenente puntatori condivisi agli oggetti [FileInfo](../../fileinfo/) che rappresentano tutte le directory situate nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) metodo


Cerca i file che soddisfano i criteri di ricerca specificati nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome dei file da cercare |

### Valore restituito

Un array di puntatori condivisi agli oggetti [FileInfo](../../fileinfo/) che rappresentano i file trovati i cui nomi corrispondono a **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) metodo


Cerca i file che soddisfano i criteri di ricerca specificati sia nella directory rappresentata dall'oggetto corrente sia nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Il modello di nome dei file da cercare |
| searchOption | [SearchOption](../../searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory rappresentata dall'oggetto corrente o nell'intero albero di directory radicato nella directory rappresentata dall'oggetto corrente |

### Valore restituito

Un array di puntatori condivisi agli oggetti [FileInfo](../../fileinfo/) che rappresentano i file trovati i cui nomi corrispondono a **searchPattern**

## Vedi anche

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [DirectoryInfo](../)
* Classe [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)