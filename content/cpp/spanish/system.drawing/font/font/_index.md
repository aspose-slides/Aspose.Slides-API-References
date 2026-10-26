---
title: Font()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase Font que representa la fuente existente especificada con el estilo de fuente especificado.
type: docs
weight: 1
url: /es/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor

Construye una nueva instancia de la clase [Font](../) que representa la fuente existente especificada con el estilo de fuente especificado.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | La fuente existente a partir de la cual crear la nueva |
| new_style | [FontStyle](../../fontstyle/) | Un estilo de fuente que se aplicará a la nueva fuente |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | La familia tipográfica de la nueva fuente |
| em_size | **float** | El tamaño em de la nueva fuente en las unidades especificadas por **unit** parameter |
| style | [FontStyle](../../fontstyle/) | El estilo de la nueva fuente |
| unit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida de la nueva fuente |
| gdi_charset | **uint8_t** | Un conjunto de caracteres GDI que se usará para la nueva fuente |
| gdi_vertical_font | **bool** | True si la nueva fuente se deriva de una fuente vertical GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor

Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | La familia tipográfica de la nueva fuente |
| em_size | **float** | El tamaño em de la nueva fuente en las unidades especificadas por **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida de la nueva fuente |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | El nombre de la familia tipográfica de la nueva fuente |
| em_size | **float** | El tamaño em de la nueva fuente en las unidades especificadas por **unit** parameter |
| style | [FontStyle](../../fontstyle/) | El estilo de la nueva fuente |
| unit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida de la nueva fuente |
| gdi_charset | **uint8_t** | Un conjunto de caracteres GDI que se usará para la nueva fuente |
| gdi_vertical_font | **bool** | True si la nueva fuente se deriva de una fuente vertical GDI |

## Font::Font(const String\&, float, GraphicsUnit) constructor

Construye una nueva instancia de la clase [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | El nombre de la familia tipográfica de la nueva fuente |
| em_size | **float** | El tamaño em de la nueva fuente en las unidades especificadas por **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida de la nueva fuente |

## Ver también

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)