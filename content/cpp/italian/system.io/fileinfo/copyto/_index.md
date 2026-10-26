---
title: CopyTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Copia il file rappresentato dall'oggetto corrente nella posizione specificata. Se il file di destinazione esiste già, la copia fallisce.
type: docs
weight: 105
url: /it/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) metodo


Copia il file rappresentato dall'oggetto corrente nella posizione specificata. Se il file di destinazione esiste già, la copia fallisce.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Il nome file di destinazione |

### Valore di ritorno

Un oggetto [FileInfo](../) che rappresenta la copia

## FileInfo::CopyTo(const String\&, bool) metodo


Copia il file rappresentato dall'oggetto corrente nella posizione specificata. Un parametro indica se il file di destinazione esistente deve essere sovrascritto.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Il nome file di destinazione |
| overwrite | **bool** | True se il file di destinazione esistente deve essere sovrascritto, false se la copia deve fallire se il file di destinazione esiste già |

### Valore di ritorno

Un oggetto [FileInfo](../) che rappresenta la copia

## Vedi anche

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)