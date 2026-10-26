---
title: DrawRectangle()
second_title: Referencia de API de Aspose.Slides para C++
description: Dibuja el rectángulo especificado usando el lápiz especificado sobre la superficie representada por el objeto actual.
type: docs
weight: 287
url: /es/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) método

Dibuja el rectángulo especificado usando el lápiz especificado sobre la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un lápiz a usar al dibujar el rectángulo |
| x | int | La coordenada X de la esquina superior izquierda del rectángulo a dibujar |
| y | int | La coordenada Y de la esquina superior izquierda del rectángulo a dibujar |
| width | int | El ancho del rectángulo a dibujar |
| height | int | La altura del rectángulo a dibujar |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) método

Dibuja el rectángulo especificado usando el lápiz especificado sobre la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un lápiz a usar al dibujar el rectángulo |
| x | **float** | La coordenada X de la esquina superior izquierda del rectángulo a dibujar |
| y | **float** | La coordenada Y de la esquina superior izquierda del rectángulo a dibujar |
| width | **float** | El ancho del rectángulo a dibujar |
| height | **float** | La altura del rectángulo a dibujar |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) método

Dibuja el rectángulo especificado usando el lápiz especificado sobre la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un lápiz a usar al dibujar el rectángulo |
| rect | [Rectangle](../../rectangle/) | Un objeto [Rectangle](../../rectangle/) que especifica la ubicación y el tamaño del rectángulo a dibujar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Pen](../../pen/)
* Clase [Graphics](../)
* Clase [Rectangle](../../rectangle/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)