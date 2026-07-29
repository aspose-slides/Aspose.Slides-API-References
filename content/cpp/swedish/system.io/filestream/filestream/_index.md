---
title: FileStream()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av klassen FileStream och initierar den med de angivna parametrarna.
type: docs
weight: 1
url: /sv/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) konstruktor


Skapar en ny instans av klassen [FileStream](../) och initierar den med de angivna parametrarna.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska öppnas. |
| mode | [FileMode](../../filemode/) | Anger läget i vilket filen ska öppnas. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) konstruktor


Skapar en ny instans av klassen [FileStream](../) och initierar den med de angivna parametrarna.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska öppnas. |
| mode | [FileMode](../../filemode/) | Anger läget i vilket filen ska öppnas. |
| access | [FileAccess](../../fileaccess/) | Den begärda åtkomsttypen. |
| share | [FileShare](../../fileshare/) | Typen av åtkomst som andra [FileStream](../)-objekt har till den öppnade filen. |
| buffer_size | **int32_t** | Antalet byte som buffras under läs- och skrivoperationer. |
| options | [FileOptions](../../fileoptions/) | Ytterligare alternativ. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) konstruktor


Skapar en ny instans av klassen [FileStream](../) och initierar den med de angivna parametrarna.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska öppnas. |
| mode | [FileMode](../../filemode/) | Anger läget i vilket filen ska öppnas. |
| access | [FileAccess](../../fileaccess/) | Den begärda åtkomsttypen. |
| share | [FileShare](../../fileshare/) | Typen av åtkomst som andra [FileStream](../)-objekt har till den öppnade filen. |
| buffer_size | **int32_t** | Antalet byte som buffras under läs- och skrivoperationer. |
| useAsync | **bool** | Anger om asynkron I/O eller synkron I/O ska användas. |
## Anmärkningar



Det underliggande operativsystemet kanske inte stöder asynkron I/O. 

## FileStream::FileStream(const FileStream\&) konstruktor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Se även

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Klass [String](../../../system/string/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)