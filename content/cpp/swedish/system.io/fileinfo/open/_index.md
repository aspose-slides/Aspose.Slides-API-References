---
title: Open()
second_title: Aspose.Slides för C++ API-referens
description: Öppnar filen som representeras av det aktuella objektet i det angivna läget för läsning och skrivning utan delning.
type: docs
weight: 183
url: /sv/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metod

Öppnar filen som representeras av det aktuella objektet i det angivna läget för läsning och skrivning utan delning.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Anger läget som filen ska öppnas i |

### Returvärde

Ett [FileStream](../../filestream/)-objekt som är associerat med filen som representeras av det aktuella objektet

## FileInfo::Open(FileMode, FileAccess) metod

Öppnar filen som representeras av det aktuella objektet i det angivna läget, med den angivna åtkomsttypen och utan delning.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Anger läget som filen ska öppnas i |
| access | [FileAccess](../../fileaccess/) | Den begärda åtkomsttypen |

### Returvärde

Ett [FileStream](../../filestream/)-objekt som är associerat med filen som representeras av det aktuella objektet

## FileInfo::Open(FileMode, FileAccess, FileShare) metod

Öppnar filen som representeras av det aktuella objektet i det angivna läget, med den angivna åtkomsttypen och delningsalternativ.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Anger läget som filen ska öppnas i |
| access | [FileAccess](../../fileaccess/) | Den begärda åtkomsttypen |
| share | [FileShare](../../fileshare/) | Typen av åtkomst som andra [FileStream](../../filestream/)-objekt har till den öppnade filen |

### Returvärde

Ett [FileStream](../../filestream/)-objekt som är associerat med filen som representeras av det aktuella objektet

## Se också

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klass [FileInfo](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)