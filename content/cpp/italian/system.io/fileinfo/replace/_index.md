---
title: Replace()
second_title: Riferimento API Aspose.Slides per C++
description: Sostituisce il contenuto di un file di destinazione specificato con il file rappresentato dall'oggetto FileInfo corrente e crea una copia di backup del file sostituito.
type: docs
weight: 131
url: /it/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) metodo


Sostituisce il contenuto di un file di destinazione specificato con il file rappresentato dall'oggetto [FileInfo](../) corrente e crea una copia di backup del file sostituito.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Il nome del file da sostituire |
| destinationBackupFileName | const [String](../../../system/string/)\& | Il nome del file di backup |

### Valore di ritorno

Un oggetto FileInfor che rappresenta il file indicato da **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) metodo


Sostituisce il contenuto di un file di destinazione specificato con il file rappresentato dall'oggetto [FileInfo](../) corrente e crea una copia di backup del file sostituito.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Il nome del file da sostituire |
| destinationBackupFileName | const [String](../../../system/string/)\& | Il nome del file di backup |
| ignoreMetadataErrors | **bool** | Specifica se gli errori di merge dal file sostituito al file di sostituzione devono essere ignorati (true) o meno (false) |

### Valore di ritorno

Un oggetto FileInfor che rappresenta il file indicato da **destinationFileName**

## Vedi anche

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [String](../../../system/string/)
* Classe [FileInfo](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)