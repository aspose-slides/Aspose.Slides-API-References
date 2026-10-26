---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar filen som representeras av det aktuella objektet till den angivna platsen. Om destinationsfilen redan finns, misslyckas kopieringen.
type: docs
weight: 105
url: /sv/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) metod

Kopierar filen som representeras av det aktuella objektet till den angivna platsen. Om destinationsfilen redan finns, misslyckas kopieringen.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Destinationsfilens namn |

### Returvärde

Ett [FileInfo](../)-objekt som representerar kopian

## FileInfo::CopyTo(const String\&, bool) metod

Kopierar filen som representeras av det aktuella objektet till den angivna platsen. En parameter anger om den befintliga destinationsfilen ska skrivas över.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Destinationsfilens namn |
| overwrite | **bool** | Sant om den befintliga destinationsfilen ska skrivas över, falskt om kopieringen ska misslyckas om destinationsfilen redan finns |

### Returvärde

Ett [FileInfo](../)-objekt som representerar kopian

## Se även

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klass [String](../../../system/string/)
* Klass [FileInfo](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)