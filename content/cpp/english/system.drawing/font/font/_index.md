---
title: Font()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of Font class that represents the specified existing font with the specified font style.
type: docs
weight: 1
url: /system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Constructs a new instance of [Font](../) class that represents the specified existing font with the specified font style.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | The existing font to create the new one from |
| new_style | [FontStyle](../../fontstyle/) | A font style to apply to the new font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const String\&, float, GraphicsUnit) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## See Also

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)