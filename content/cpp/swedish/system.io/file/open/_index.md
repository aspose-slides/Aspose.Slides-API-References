---
title: Open()
second_title: Aspose.Slides för C++ API-referens
description: Öppnar den angivna filen i det angivna läget för läsning och skrivning utan delning.
type: docs
weight: 235
url: /sv/system.io/file/open/
---
## File::Open(const String\&, FileMode) metod


Öppnar den angivna filen i det angivna läget för läsning och skrivning utan delning.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska öppnas |
| mode | [FileMode](../../filemode/) | Anger läget i vilket filen ska öppnas |

### Returvärde

Ett [FileStream](../../filestream/)-objekt associerat med den öppnade filen

## File::Open(const String\&, FileMode, FileAccess, FileShare) metod


Öppnar den angivna filen i det angivna läget, med den angivna åtkomsttypen och delningsalternativet.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska öppnas |
| mode | [FileMode](../../filemode/) | Anger läget i vilket filen ska öppnas |
| access | [FileAccess](../../fileaccess/) | Den begärda åtkomsttypen |
| share | [FileShare](../../fileshare/) | Typen av åtkomst som andra [FileStream](../../filestream/)-objekt har till den öppnade filen |

### Returvärde

Ett [FileStream](../../filestream/)-objekt associerat med den öppnade filen

## Se även

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* klass [String](../../../system/string/)
* klass [File](../)
* namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)