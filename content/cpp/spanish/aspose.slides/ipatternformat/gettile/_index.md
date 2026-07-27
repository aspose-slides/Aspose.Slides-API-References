---
title: GetTile()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una imagen de mosaico para el relleno de patrón con colores especificados.
type: docs
weight: 53
url: /es/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) método

Crea una imagen de mosaico para el relleno de patrón con colores especificados.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | El [System::Drawing::Color](../../../system.drawing/color/) de fondo para el patrón. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | El [System::Drawing::Color](../../../system.drawing/color/) de primer plano para el patrón. |

### Valor devuelto

Mosaico [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) método

Crea una imagen de mosaico para el relleno del patrón.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | El [System::Drawing::Color](../../../system.drawing/color/) predeterminado, definido en el objeto StyleEx de ShapeEx. Los colores del relleno pueden depender de esto. |

### Valor devuelto

Mosaico [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../iimage/)
* Clase [Color](../../../system.drawing/color/)
* Clase [IPatternFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)