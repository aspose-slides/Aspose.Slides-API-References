---
title: FileStream()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci třídy FileStream a inicializuje ji zadanými parametry.
type: docs
weight: 1
url: /cs/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) konstruktor


Vytvoří novou instanci třídy [FileStream](../) a inicializuje ji zadanými parametry.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má otevřít. |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém se má soubor otevřít. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) konstruktor


Vytvoří novou instanci třídy [FileStream](../) a inicializuje ji zadanými parametry.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má otevřít. |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém se má soubor otevřít. |
| access | [FileAccess](../../fileaccess/) | Požadovaný typ přístupu. |
| share | [FileShare](../../fileshare/) | Typ přístupu, který mají ostatní objekty [FileStream](../) k otevřenému souboru. |
| buffer_size | **int32_t** | Počet bajtů bufferovaných během operací čtení a zápisu. |
| options | [FileOptions](../../fileoptions/) | Další možnosti. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) konstruktor


Vytvoří novou instanci třídy [FileStream](../) a inicializuje ji zadanými parametry.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má otevřít. |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém se má soubor otevřít. |
| access | [FileAccess](../../fileaccess/) | Požadovaný typ přístupu. |
| share | [FileShare](../../fileshare/) | Typ přístupu, který mají ostatní objekty [FileStream](../) k otevřenému souboru. |
| buffer_size | **int32_t** | Počet bajtů bufferovaných během operací čtení a zápisu. |
| useAsync | **bool** | Určuje, zda používat asynchronní I/O nebo synchronní I/O. |
## Poznámky



Podkladový operační systém nemusí podporovat asynchronní I/O. 

## FileStream::FileStream(const FileStream\&) konstruktor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Viz také

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)