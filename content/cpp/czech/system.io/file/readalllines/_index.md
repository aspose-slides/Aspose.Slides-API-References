---
title: ReadAllLines()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Načte obsah zadaného textového souboru řádek po řádku do pole řetězců pomocí zadaného kódování znaků.
type: docs
weight: 300
url: /cs/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metoda


Načte obsah zadaného textového souboru řádek po řádku do pole řetězců pomocí zadaného kódování znaků.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má načíst |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

### Návratová hodnota

Pole řetězců, kde každý prvek představuje jeden řádek ze zadaného souboru

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)