---
title: ReadLines()
second_title: Aspose.Slides pro C++ - reference API
description: Načte obsah zadaného textového souboru řádek po řádku pomocí zadaného kódování znaků a vrátí výčtovou kolekci řetězců, z nichž každý představuje jeden řádek obsahu souboru.
type: docs
weight: 326
url: /cs/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metoda


Načte obsah zadaného textového souboru řádek po řádku pomocí zadaného kódování znaků a vrátí výčtovou kolekci řetězců, z nichž každý představuje jeden řádek obsahu souboru.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má přečíst |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

### Návratová hodnota

Výčtová kolekce řetězců představující obsah zadaného souboru

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)