---
title: Open()
second_title: Riferimento API di Aspose.Slides per C++
description: Apre il file specificato nella modalità specificata per lettura e scrittura senza condivisione.
type: docs
weight: 235
url: /it/system.io/file/open/
---
## File::Open(const String&, FileMode) metodo

Apre il file specificato nella modalità specificata per lettura e scrittura e senza condivisione.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da aprire |
| mode | [FileMode](../../filemode/) | Specifica la modalità con cui aprire il file |

### Valore di ritorno

Un oggetto [FileStream](../../filestream/) associato al file aperto

## File::Open(const String&, FileMode, FileAccess, FileShare) metodo

Apre il file specificato nella modalità specificata, con il tipo di accesso specificato e l'opzione di condivisione.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da aprire |
| mode | [FileMode](../../filemode/) | Specifica la modalità con cui aprire il file |
| access | [FileAccess](../../fileaccess/) | Il tipo di accesso richiesto |
| share | [FileShare](../../fileshare/) | Il tipo di accesso che altri oggetti [FileStream](../../filestream/) hanno al file aperto |

### Valore di ritorno

Un oggetto [FileStream](../../filestream/) associato al file aperto

## Vedi anche

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)