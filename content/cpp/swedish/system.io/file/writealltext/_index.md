---
title: WriteAllText()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny textfil eller skriver över den befintliga och skriver innehållet i den angivna strängen till den med den angivna kodningen.
type: docs
weight: 469
url: /sv/system.io/file/writealltext/
---
## File::WriteAllText(const String&, const String&, const EncodingPtr&) metod

Skapar en ny textfil eller skriver över den befintliga och skriver innehållet i den angivna strängen till den med den angivna kodningen.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Filen att skapa eller skriva över |
| contents | const [String](../../../system/string/)\& | En array av strängar |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodningen att använda |

## Se även

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)