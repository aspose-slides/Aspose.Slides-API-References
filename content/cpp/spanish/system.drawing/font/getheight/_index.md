---
title: GetHeight()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el interlineado de la fuente representada por el objeto actual, en la unidad actual de un objeto Graphics especificado.
type: docs
weight: 14
url: /es/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) method


Devuelve el interlineado de la fuente representada por el objeto actual, en la unidad actual de un objeto [Graphics](../../graphics/) especificado.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Un objeto [Graphics](../../graphics/) que especifica las unidades de medida |

## Font::GetHeight(float) method


Devuelve la altura de la fuente representada por el objeto actual cuando se dibuja en un dispositivo de visualización con la resolución vertical especificada.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpi | **float** | La resolución vertical del dispositivo de visualización |

### Valor devuelto

La altura de la fuente en píxeles

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Graphics](../../graphics/)
* Clase [Font](../)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)