---
title: ReadAllText()
second_title: Aspose.Slides pro C++ API Referenci
description: Načte obsah zadaného textového souboru do jediného objektu String pomocí zadaného kódování znaků.
type: docs
weight: 313
url: /cs/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) metoda

Přečte obsah zadaného textového souboru do jediného [String](../../../system/string/) objektu pomocí zadaného kódování znaků.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má načíst |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

### Návratová hodnota

Řetězec obsahující obsah zadaného souboru

## Viz také

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)