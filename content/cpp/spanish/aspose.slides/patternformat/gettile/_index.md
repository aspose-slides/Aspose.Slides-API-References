---
title: GetTile()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una imagen de mosaico para el relleno de patrón con colores especificados.
type: docs
weight: 53
url: /es/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) método

Crea una imagen de mosaico para el relleno de patrón con colores especificados.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | El fondo [System::Drawing::Color](../../../system.drawing/color/) del patrón. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | El primer plano [System::Drawing::Color](../../../system.drawing/color/) del patrón. |

### Valor devuelto

Mosaico [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) método

Crea una imagen de mosaico para el relleno de patrón.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | El valor predeterminado [System::Drawing::Color](../../../system.drawing/color/) |

### Valor devuelto

Mosaico [IImage](../../iimage/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* clase [IImage](../../iimage/)
* clase [Color](../../../system.drawing/color/)
* clase [PatternFormat](../)
* espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)