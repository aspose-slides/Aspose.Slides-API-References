---
title: Copy()
second_title: Riferimento API Aspose.Slides per C++
description: Copia il file specificato nella posizione specificata. Se il file di destinazione esiste già, un parametro specifica se deve essere sovrascritto.
type: docs
weight: 40
url: /it/system.io/file/copy/
---
## File::Copy(const String&, const String&, bool) metodo

Copia il file specificato nella posizione specificata. Se il file di destinazione esiste già, un parametro specifica se deve essere sovrascritto.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Un percorso del file da copiare |
| destFileName | const [String](../../../system/string/)\& | Un percorso della nuova posizione del file da copiare |
| overwrite | **bool** | True se il file di destinazione esistente deve essere sovrascritto, false se la copia deve fallire se il file di destinazione esiste già |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)