---
title: Open()
second_title: Riferimento API di Aspose.Slides per C++
description: Apre il file rappresentato dall'oggetto corrente nella modalità specificata per lettura e scrittura e senza condivisione.
type: docs
weight: 183
url: /it/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metodo


Apre il file rappresentato dall'oggetto corrente nella modalità specificata per lettura e scrittura e senza condivisione.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specifica la modalità in cui aprire il file |

### Valore di ritorno

Un oggetto [FileStream](../../filestream/) associato al file rappresentato dall'oggetto corrente

## FileInfo::Open(FileMode, FileAccess) metodo


Apre il file rappresentato dall'oggetto corrente nella modalità specificata, con il tipo di accesso specificato e senza condivisione.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specifica la modalità in cui aprire il file |
| access | [FileAccess](../../fileaccess/) | Il tipo di accesso richiesto |

### Valore di ritorno

Un oggetto [FileStream](../../filestream/) associato al file rappresentato dall'oggetto corrente

## FileInfo::Open(FileMode, FileAccess, FileShare) metodo


Apre il file rappresentato dall'oggetto corrente nella modalità specificata, con il tipo di accesso specificato e l'opzione di condivisione.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specifica la modalità in cui aprire il file |
| access | [FileAccess](../../fileaccess/) | Il tipo di accesso richiesto |
| share | [FileShare](../../fileshare/) | Il tipo di accesso che altri oggetti [FileStream](../../filestream/) hanno al file aperto |

### Valore di ritorno

Un oggetto [FileStream](../../filestream/) associato al file rappresentato dall'oggetto corrente

## Vedi anche

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)