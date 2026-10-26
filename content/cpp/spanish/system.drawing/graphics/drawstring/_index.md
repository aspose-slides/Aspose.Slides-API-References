---
title: DrawString()
second_title: Referencia de API de Aspose.Slides para C++
description: Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados.
type: docs
weight: 365
url: /es/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) método

Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La cadena a dibujar |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Una fuente para usar |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objeto [Brush](../../brush/) para usar en el dibujo |
| topLeft | [PointF](../../pointf/) | Especifica la ubicación de la esquina superior izquierda de la cadena dibujada |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Especifica el formato de la cadena |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) método

Dibuja la cadena especificada en el rectángulo especificado usando la fuente y el pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La cadena a dibujar |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Una fuente para usar |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objeto [Brush](../../brush/) para usar en el dibujo |
| layoutRectangle | [RectangleF](../../rectanglef/) | Especifica un rectángulo en el que dibujar la cadena |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Especifica el formato de la cadena |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) método

Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La cadena a dibujar |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Una fuente para usar |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objeto [Brush](../../brush/) para usar en el dibujo |
| x | **float** | La coordenada X de la ubicación de la esquina superior izquierda de la cadena dibujada |
| y | **float** | La coordenada Y de la ubicación de la esquina superior izquierda de la cadena dibujada |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Especifica el formato de la cadena |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Font](../../font/)
* Clase [Brush](../../brush/)
* Clase [PointF](../../pointf/)
* Clase [StringFormat](../../stringformat/)
* Clase [Graphics](../)
* Clase [RectangleF](../../rectanglef/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)