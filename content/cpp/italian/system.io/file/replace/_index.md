---
title: Replace()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce il contenuto di un file con un altro e crea una copia di backup del file sostituito.
type: docs
weight: 339
url: /it/system.io/file/replace/
---
## File::Replace(const String&, const String&, const String&, bool) metodo


Sostituisce il contenuto di un file con un altro e crea una copia di backup del file sostituito.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Il nome del file con cui sostituire |
| destinationFileName | const [String](../../../system/string/)\& | Il nome del file da sostituire |
| destinationBackupFileName | const [String](../../../system/string/)\& | Il nome del file di backup |
| ignoreMetadataErrors | **bool** | Specifica se gli errori di unione dal file sostituito al file di sostituzione devono essere ignorati (true) o no (false) |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)