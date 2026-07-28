---
title: Font()
second_title: Aspose.Slides C++ API referenciája
description: Új példányt hoz létre a Font osztályból, amely a megadott meglévő betűtípust a megadott betűtípus-stílussal ábrázolja.
type: docs
weight: 1
url: /hu/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor

Létrehoz egy új példányt a [Font](../) osztályból, amely a megadott létező betűtípust a megadott betűtípus-stílussal ábrázolja.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | A meglévő betűtípus, amelyből az újat létrehozzuk |
| new_style | [FontStyle](../../fontstyle/) | A betűtípus-stílus, amelyet az új betűtípusra alkalmazunk |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Létrehoz egy új példányt a [Font](../) osztályból.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Az új betűtípus betűtípus-családja |
| em_size | **float** | Az új betűtípus em-mérete a **unit** paraméterben megadott egységekben |
| style | [FontStyle](../../fontstyle/) | Az új betűtípus stílusa |
| unit | [GraphicsUnit](../../graphicsunit/) | Az új betűtípus mértékegysége |
| gdi_charset | **uint8_t** | A GDI karakterkészlet, amelyet az új betűtípus használ |
| gdi_vertical_font | **bool** | Igaz, ha az új betűtípus egy GDI függőleges betűtípusból származik |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor

Létrehoz egy új példányt a [Font](../) osztályból.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Az új betűtípus betűtípus-családja |
| em_size | **float** | Az új betűtípus em-mérete a **unit** paraméterben megadott egységekben |
| unit | [GraphicsUnit](../../graphicsunit/) | Az új betűtípus mértékegysége |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Létrehoz egy új példányt a [Font](../) osztályból.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Az új betűtípus betűtípus-családjának neve |
| em_size | **float** | Az új betűtípus em-mérete a **unit** paraméterben megadott egységekben |
| style | [FontStyle](../../fontstyle/) | Az új betűtípus stílusa |
| unit | [GraphicsUnit](../../graphicsunit/) | Az új betűtípus mértékegysége |
| gdi_charset | **uint8_t** | A GDI karakterkészlet, amelyet az új betűtípus használ |
| gdi_vertical_font | **bool** | Igaz, ha az új betűtípus egy GDI függőleges betűtípusból származik |

## Font::Font(const String\&, float, GraphicsUnit) constructor

Létrehoz egy új példányt a [Font](../) osztályból.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Az új betűtípus betűtípus-családjának neve |
| em_size | **float** | Az új betűtípus em-mérete a **unit** paraméterben megadott egységekben |
| unit | [GraphicsUnit](../../graphicsunit/) | Az új betűtípus mértékegysége |

## Lásd még

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)