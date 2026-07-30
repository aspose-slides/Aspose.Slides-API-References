---
title: OpenText()
second_title: Aspose.Slides pro C++ – reference API
description: Otevře zadaný existující soubor pro čtení textu s kódováním UTF-8 bez sdílení.
type: docs
weight: 261
url: /cs/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) metoda


Otevře určený existující soubor pro čtení textu s kódováním UTF-8 bez sdílení.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má otevřít |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

## Návratová hodnota

Sdílený ukazatel na objekt [StreamWriter](../../streamwriter/) spojený s otevřeným souborem

## Viz také

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)