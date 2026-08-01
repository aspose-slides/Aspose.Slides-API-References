---
title: Font()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de Font-klasse dat het opgegeven bestaande lettertype vertegenwoordigt met de opgegeven lettertype-stijl.
type: docs
weight: 1
url: /nl/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Construeert een nieuw exemplaar van de klasse [Font](../) dat de opgegeven bestaande lettertype vertegenwoordigt met de opgegeven lettertype-stijl.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | The existing font to create the new one from |
| new_style | [FontStyle](../../fontstyle/) | A font style to apply to the new font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Construeert een nieuw exemplaar van de klasse [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Construeert een nieuw exemplaar van de klasse [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Construeert een nieuw exemplaar van de klasse [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const String\&, float, GraphicsUnit) constructor


Construeert een nieuw exemplaar van de klasse [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## Zie ook

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)