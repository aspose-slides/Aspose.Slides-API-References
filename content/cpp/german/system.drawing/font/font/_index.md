---
title: Font()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt eine neue Instanz der Klasse Font, die die angegebene vorhandene Schriftart mit dem angegebenen Schriftschnitt darstellt.
type: docs
weight: 1
url: /de/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor

Erzeugt eine neue Instanz der Klasse [Font](../), die die angegebene vorhandene Schriftart mit dem angegebenen Schriftschnitt darstellt.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Die vorhandene Schriftart, aus der die neue erstellt werden soll |
| new_style | [FontStyle](../../fontstyle/) | Ein Schriftschnitt, der auf die neue Schriftart angewendet werden soll |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Erzeugt eine neue Instanz der Klasse [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Die Schriftfamilie der neuen Schriftart |
| em_size | **float** | Die Em-Größe der neuen Schriftart in den durch den Parameter **unit** angegebenen Einheiten |
| style | [FontStyle](../../fontstyle/) | Der Stil der neuen Schriftart |
| unit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheit der neuen Schriftart |
| gdi_charset | **uint8_t** | Ein GDI-Zeichensatz, der für die neue Schriftart verwendet werden soll |
| gdi_vertical_font | **bool** | Wahr, wenn die neue Schriftart von einer GDI-vertikalen Schriftart abgeleitet ist |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor

Erzeugt eine neue Instanz der Klasse [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Die Schriftfamilie der neuen Schriftart |
| em_size | **float** | Die Em-Größe der neuen Schriftart in den durch den Parameter **unit** angegebenen Einheiten |
| unit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheit der neuen Schriftart |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Erzeugt eine neue Instanz der Klasse [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Der Name der Schriftfamilie der neuen Schriftart |
| em_size | **float** | Die Em-Größe der neuen Schriftart in den durch den Parameter **unit** angegebenen Einheiten |
| style | [FontStyle](../../fontstyle/) | Der Stil der neuen Schriftart |
| unit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheit der neuen Schriftart |
| gdi_charset | **uint8_t** | Ein GDI-Zeichensatz, der für die neue Schriftart verwendet werden soll |
| gdi_vertical_font | **bool** | Wahr, wenn die neue Schriftart von einer GDI-vertikalen Schriftart abgeleitet ist |

## Font::Font(const String\&, float, GraphicsUnit) constructor

Erzeugt eine neue Instanz der Klasse [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Der Name der Schriftfamilie der neuen Schriftart |
| em_size | **float** | Die Em-Größe der neuen Schriftart in den durch den Parameter **unit** angegebenen Einheiten |
| unit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheit der neuen Schriftart |

## Siehe auch

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)