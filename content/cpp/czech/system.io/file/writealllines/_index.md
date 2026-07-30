---
title: WriteAllLines()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový textový soubor nebo přepíše existující a zapíše všechny řetězce ze specifikované výčtové kolekce řetězců do něj, každý řetězec na nový řádek, pomocí zadaného kódování.
type: docs
weight: 456
url: /cs/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metoda

Vytvoří nový textový soubor nebo přepíše existující a zapíše všechny řetězce ze zadané výčtové kolekce řetězců do něj, každý řetězec na nový řádek, pomocí zadaného kódování.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Soubor, který se má vytvořit nebo přepsat |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Výčtová kolekce řetězců |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) metoda

Vytvoří nový textový soubor nebo přepíše existující a zapíše všechny řetězce ze zadaného pole řetězců do něj, každý řetězec na nový řádek, pomocí zadaného kódování.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Soubor, který se má vytvořit nebo přepsat |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Pole řetězců |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)