---
title: FontFamily()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο στιγμιότυπο της κλάσης FontFamily που αντιπροσωπεύει μια οικογένεια γραμματοσειρών με το καθορισμένο όνομα.
type: docs
weight: 1
url: /el/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../) που αντιπροσωπεύει μια οικογένεια γραμματοσειρών με το καθορισμένο όνομα.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A font family name |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor


Δημιουργεί ένα νέο στιγμιότυπο του [FontFamily](../) στη συγκεκριμένη FontCollection με το καθορισμένο όνομα.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A font family name |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | The FontCollection what contains this instance. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor


Δημιουργεί ένα νέο στιγμιότυπο του [FontFamily](../) από την καθορισμένη γενική οικογένεια γραμματοσειρών.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | The GenericFontFamilies value to construct the [FontFamily](../). |

## See Also

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../)
* Class [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)