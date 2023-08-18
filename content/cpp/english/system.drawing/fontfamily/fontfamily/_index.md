---
title: FontFamily()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of FontFamily class that represents a font family with the specified name.
type: docs
weight: 1
url: /system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor


Constructs a new instance of [FontFamily](../) class that represents a font family with the specified name.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A font family name |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor


Constructs a new instance of [FontFamily](../) in the specified FontCollection with the specified name.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A font family name |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | The FontCollection what contains this instance. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor


Constructs a new instance of [FontFamily](../) from the specified generic font family.

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