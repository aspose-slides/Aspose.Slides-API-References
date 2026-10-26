---
title: FontFamily()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy új példányt a FontFamily osztályból, amely a megadott névvel rendelkező betűkészletet képviseli.
type: docs
weight: 1
url: /hu/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) konstruktor


Létrehoz egy új példányt a(z) [FontFamily](../) osztályból, amely a megadott névvel rendelkező betűkészletet képviseli.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Egy betűkészlet neve |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) konstruktor


Létrehoz egy új példányt a(z) [FontFamily](../) osztályból a megadott FontCollection-ben a megadott névvel.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Egy betűkészlet neve |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | A FontCollection, amely tartalmazza ezt a példányt. |

## FontFamily::FontFamily(Text::GenericFontFamilies) konstruktor


Létrehoz egy új példányt a(z) [FontFamily](../) osztályból a megadott általános betűkészletből.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | A GenericFontFamilies érték a(z) [FontFamily](../) létrehozásához. |

## Lásd még

* Felsorolat [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [FontFamily](../)
* Osztály [FontCollection](../../../system.drawing.text/fontcollection/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)