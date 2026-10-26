---
title: FontFamily()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz der FontFamily Klasse, die eine Schriftfamilie mit dem angegebenen Namen darstellt.
type: docs
weight: 1
url: /de/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) Konstruktor


Erstellt eine neue Instanz von [FontFamily](../) Klasse, die eine Schriftfamilie mit dem angegebenen Namen darstellt.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Ein Font-Familienname |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) Konstruktor


Erstellt eine neue Instanz von [FontFamily](../) in der angegebenen FontCollection mit dem angegebenen Namen.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Ein Font-Familienname |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | Die FontCollection, die diese Instanz enthält. |

## FontFamily::FontFamily(Text::GenericFontFamilies) Konstruktor


Erstellt eine neue Instanz von [FontFamily](../) aus der angegebenen generischen Schriftfamilie.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | Der GenericFontFamilies-Wert zum Erstellen des [FontFamily](../). |

## Siehe auch

* Aufzählung [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFamily](../)
* Klasse [FontCollection](../../../system.drawing.text/fontcollection/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)