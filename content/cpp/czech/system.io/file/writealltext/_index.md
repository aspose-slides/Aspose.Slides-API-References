---
title: WriteAllText()
second_title: Aspose.Slides pro C++ API Referenci
description: Vytvoří nový textový soubor nebo přepíše existující a zapíše obsah určeného řetězce do něj pomocí zadaného kódování.
type: docs
weight: 469
url: /cs/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) metoda

Vytvoří nový textový soubor nebo přepíše existující a zapíše obsah zadaného řetězce do něj pomocí zadaného kódování.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Soubor, který vytvořit nebo přepsat |
| contents | const [String](../../../system/string/)\& | Pole řetězců |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

## Viz také

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)