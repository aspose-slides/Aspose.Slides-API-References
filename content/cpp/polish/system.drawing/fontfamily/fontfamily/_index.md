---
title: FontFamily()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy nową instancję klasy FontFamily, która reprezentuje rodzinę czcionek o określonej nazwie.
type: docs
weight: 1
url: /pl/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) konstruktor


Tworzy nową instancję klasy [FontFamily](../), która reprezentuje rodzinę czcionek o podanej nazwie.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa rodziny czcionek |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) konstruktor


Tworzy nową instancję [FontFamily](../) w określonej FontCollection o podanej nazwie.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa rodziny czcionek |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollection, która zawiera tę instancję. |

## FontFamily::FontFamily(Text::GenericFontFamilies) konstruktor


Tworzy nową instancję [FontFamily](../) z określonej ogólnej rodziny czcionek.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | Wartość GenericFontFamilies używana do utworzenia [FontFamily](../). |

## Zobacz także

* Wyliczenie [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* DefinicjaTypu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [FontFamily](../)
* Klasa [FontCollection](../../../system.drawing.text/fontcollection/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)