---
title: FontFamily()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av klassen FontFamily som representerar en teckensnittsfamilj med det angivna namnet.
type: docs
weight: 1
url: /sv/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor


Skapar en ny instans av klassen [FontFamily](../) som representerar en teckensnittsfamilj med det angivna namnet.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på teckensnittsfamiljen |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor


Skapar en ny instans av [FontFamily](../) i den angivna FontCollection med det angivna namnet.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på teckensnittsfamiljen |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollection som innehåller denna instans. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor


Skapar en ny instans av [FontFamily](../) från den angivna generiska teckensnittsfamiljen.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | GenericFontFamilies-värdet för att konstruera [FontFamily](../). |

## Se även

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [FontFamily](../)
* Klass [FontCollection](../../../system.drawing.text/fontcollection/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)