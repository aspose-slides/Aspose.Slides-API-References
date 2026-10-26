---
title: Copy()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar den angivna filen till den angivna platsen. Om målfilen redan finns anger en parameter om den ska skrivas över.
type: docs
weight: 40
url: /sv/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) metod

Kopierar den angivna filen till den angivna platsen. Om målfilen redan finns, anger en parameter om den ska skrivas över.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Sökväg till filen som ska kopieras |
| destFileName | const [String](../../../system/string/)\& | Sökväg till den nya platsen för filen som ska kopieras |
| overwrite | **bool** | True om den befintliga målfilen ska skrivas över, false om kopieringen ska misslyckas när målfilen redan finns |

## Se också

* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)