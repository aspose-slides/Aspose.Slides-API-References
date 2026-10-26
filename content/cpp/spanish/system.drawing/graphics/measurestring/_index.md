---
title: MeasureString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.
type: docs
weight: 521
url: /es/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | La cadena cuyo tamaño se calculará |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | La fuente usada para dibujar la cadena |
| origin | [PointF](../../pointf/) const\& | Especifica la ubicación de la esquina superior izquierda de la cadena |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Especifica el formato de la cadena |

### Valor devuelto

Un objeto [SizeF](../../sizef/) que representa el tamaño de la cadena en las unidades de medida especificadas por la propiedad PageUnit del objeto Grapphics actual.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | La cadena cuyo tamaño se calculará |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | La fuente usada para dibujar la cadena |
| width | int | El ancho máximo de la cadena |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Especifica el formato de la cadena |

### Valor devuelto

Un objeto [SizeF](../../sizef/) que representa el tamaño de la cadena en las unidades de medida especificadas por la propiedad PageUnit del objeto Grapphics actual.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

NO IMPLEMENTADO.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | La cadena cuyo tamaño se calculará |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | La fuente usada para dibujar la cadena |
| layoutArea | [SizeF](../../sizef/) const\& | El área máxima de disposición de la cadena |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Especifica el formato de la cadena |

### Valor devuelto

Un objeto [SizeF](../../sizef/) que representa el tamaño de la cadena en las unidades de medida especificadas por la propiedad PageUnit del objeto Grapphics actual.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [SizeF](../../sizef/)
* Clase [String](../../../system/string/)
* Clase [Font](../../font/)
* Clase [PointF](../../pointf/)
* Clase [StringFormat](../../stringformat/)
* Clase [Graphics](../)
* Espacio de nombres [System::Drawing](../../)
* Library [Aspose.Slides](../../../)