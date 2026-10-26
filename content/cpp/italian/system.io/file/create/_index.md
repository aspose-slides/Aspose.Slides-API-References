---
title: Create()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo file (o sovrascrive quello esistente) e lo apre per l'accesso in lettura e scrittura utilizzando la dimensione del buffer e le opzioni specificate.
type: docs
weight: 53
url: /it/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) metodo

Crea un nuovo file (o sovrascrive quello esistente) e lo apre per l'accesso in lettura e scrittura utilizzando la dimensione del buffer e le opzioni specificate.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da creare o sovrascrivere |
| bufferSize | **int32_t** | Il numero di byte memorizzati nel buffer durante la lettura e la scrittura del file |
| options | [FileOptions](../../fileoptions/) | Specifica come creare o sovrascrivere il file |

### Valore di ritorno

Un puntatore condiviso all'oggetto [FileStream](../../filestream/) associato al file specificato

## Vedi anche

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)