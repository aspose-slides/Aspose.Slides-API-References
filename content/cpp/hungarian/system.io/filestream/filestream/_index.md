---
title: FileStream()
second_title: Aspose.Slides C++ API referenciája
description: Új példányt hoz létre a FileStream osztályból, és a megadott paraméterekkel inicializálja.
type: docs
weight: 1
url: /hu/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) konstruktor


Új példányt hoz létre a(z) [FileStream](../) osztályból, és a megadott paraméterekkel inicializálja.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó fájl elérési útja. |
| mode | [FileMode](../../filemode/) | Megadja a fájl megnyitásának módját. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) konstruktor


Új példányt hoz létre a(z) [FileStream](../) osztályból, és a megadott paraméterekkel inicializálja.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó fájl elérési útja. |
| mode | [FileMode](../../filemode/) | Megadja a fájl megnyitásának módját. |
| access | [FileAccess](../../fileaccess/) | A kért hozzáférési típus. |
| share | [FileShare](../../fileshare/) | Az a hozzáférés típusa, amelyet más [FileStream](../) objektumok a megnyitott fájlhoz rendelkeznek. |
| buffer_size | **int32_t** | A beolvasási és írási műveletek során pufferelt byte-ok száma. |
| options | [FileOptions](../../fileoptions/) | További opciók. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) konstruktor


Új példányt hoz létre a(z) [FileStream](../) osztályból, és a megadott paraméterekkel inicializálja.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó fájl elérési útja. |
| mode | [FileMode](../../filemode/) | Megadja a fájl megnyitásának módját. |
| access | [FileAccess](../../fileaccess/) | A kért hozzáférési típus. |
| share | [FileShare](../../fileshare/) | Az a hozzáférés típusa, amelyet más [FileStream](../) objektumok a megnyitott fájlhoz rendelkeznek. |
| buffer_size | **int32_t** | A beolvasási és írási műveletek során pufferelt byte-ok száma. |
| useAsync | **bool** | Megadja, hogy aszinkron I/O-t vagy szinkron I/O-t kell használni. |

## Megjegyzések



Az alapul szolgáló operációs rendszer nem feltétlenül támogatja az aszinkron I/O-t. 

## FileStream::FileStream(const FileStream\&) konstruktor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Lásd még

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Osztály [String](../../../system/string/)
* Osztály [FileStream](../)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)