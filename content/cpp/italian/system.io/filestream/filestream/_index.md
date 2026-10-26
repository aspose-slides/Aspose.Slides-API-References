---
title: FileStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe FileStream e la inizializza con i parametri specificati.
type: docs
weight: 1
url: /it/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) costruttore


Costruisce una nuova istanza della classe [FileStream](../) e la inizializza con i parametri specificati.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da aprire. |
| mode | [FileMode](../../filemode/) | Specifica la modalità con cui aprire il file. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) costruttore


Costruisce una nuova istanza della classe [FileStream](../) e la inizializza con i parametri specificati.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da aprire. |
| mode | [FileMode](../../filemode/) | Specifica la modalità con cui aprire il file. |
| access | [FileAccess](../../fileaccess/) | Il tipo di accesso richiesto. |
| share | [FileShare](../../fileshare/) | Il tipo di accesso che altri oggetti [FileStream](../) hanno sul file aperto. |
| buffer_size | **int32_t** | Il numero di byte memorizzati nel buffer durante le operazioni di lettura e scrittura. |
| options | [FileOptions](../../fileoptions/) | Opzioni aggiuntive. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) costruttore


Costruisce una nuova istanza della classe [FileStream](../) e la inizializza con i parametri specificati.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da aprire. |
| mode | [FileMode](../../filemode/) | Specifica la modalità con cui aprire il file. |
| access | [FileAccess](../../fileaccess/) | Il tipo di accesso richiesto. |
| share | [FileShare](../../fileshare/) | Il tipo di accesso che altri oggetti [FileStream](../) hanno sul file aperto. |
| buffer_size | **int32_t** | Il numero di byte memorizzati nel buffer durante le operazioni di lettura e scrittura. |
| useAsync | **bool** | Specifica se utilizzare I/O asincrono o I/O sincrono. |
## Osservazioni



Il sistema operativo sottostante potrebbe non supportare I/O asincrono. 

## FileStream::FileStream(const FileStream\&) costruttore




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Vedi anche

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)