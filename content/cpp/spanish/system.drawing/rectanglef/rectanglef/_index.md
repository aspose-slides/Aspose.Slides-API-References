---
title: RectangleF()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia del objeto RectangleF que representa un rectángulo con coordenadas X e Y y valores de ancho y altura establecidos a 0.
type: docs
weight: 1
url: /es/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() constructor


Construye una nueva instancia del objeto [RectangleF](../) que representa un rectángulo con coordenadas X e Y y valores de ancho y hegiht establecidos a 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) constructor


Construye una nueva instancia del objeto [RectangleF](../) que representa un rectángulo con las coordenadas especificadas de su esquina superior izquierda y su ancho y altura.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | Un valor de la coordenada X de la esquina superior izquierda del rectángulo |
| y | **float** | Un valor de la coordenada Y de la esquina superior izquierda del rectángulo |
| width | **float** | El ancho del rectángulo |
| height | **float** | La altura del rectángulo |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) constructor


Construye una nueva instancia del objeto [RectangleF](../) que representa un rectángulo con las coordenadas de su esquina superior izquierda especificadas como una instancia de la clase [PointF](../../pointf/) y su ancho y altura como una instancia de la clase [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Especifica la ubicación de la esquina superior izquierda del rectángulo |
| size | const [SizeF](../../sizef/)\& | Especifica el ancho y hegiht del rectángulo |

## RectangleF::RectangleF(const Rectangle\&) constructor


Construye una nueva instancia del objeto [RectangleF](../) que representa el rectángulo equivalente al especificado.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Una instancia de la clase [Rectangle](../../rectangle/) que especifica la posición y el tamaño del rectángulo que será representado por el objeto que se está construyendo |

## Ver también

* Clase [RectangleF](../)
* Clase [PointF](../../pointf/)
* Clase [SizeF](../../sizef/)
* Clase [Rectangle](../../rectangle/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)