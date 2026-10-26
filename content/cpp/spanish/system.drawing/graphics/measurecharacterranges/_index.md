---
title: MeasureCharacterRanges()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una matriz de regiones, cada una de las cuales delimita las posiciones de los caracteres en la cadena especificada.
type: docs
weight: 508
url: /es/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) método

Devuelve una matriz de regiones, cada una de las cuales delimita posiciones de caracteres en la cadena especificada.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | La cadena a medir |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | La fuente utilizada durante la medición de la cadena |
| layoutRect | [RectangleF](../../rectanglef/) | El rectángulo de disposición utilizado durante la medición de la cadena |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | El formato de cadena, que contiene los rangos de caracteres a medir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Region](../../region/)
* Clase [String](../../../system/string/)
* Clase [Font](../../font/)
* Clase [RectangleF](../../rectanglef/)
* Clase [StringFormat](../../stringformat/)
* Clase [Graphics](../)
* Espacio de nombres [System::Drawing](../../)
* Library [Aspose.Slides](../../../)