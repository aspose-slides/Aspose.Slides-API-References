---
title: Rectangle()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia del objeto Rectangle que representa un rectángulo con coordenadas X e Y y valores de ancho y altura establecidos en 0.
type: docs
weight: 1
url: /es/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() constructor

Construye una nueva instancia del objeto [Rectangle](../) que representa un rectángulo con coordenadas X e Y y valores de ancho y altura establecidos en 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) constructor

Construye una nueva instancia del objeto [Rectangle](../) que representa un rectángulo con las coordenadas especificadas de su esquina superior izquierda y su ancho y altura.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | Un valor de la coordenada X de la esquina superior izquierda del rectángulo |
| y | int | Un valor de la coordenada Y de la esquina superior izquierda del rectángulo |
| width | int | El ancho del rectángulo |
| height | int | La altura del rectángulo |

## Rectangle::Rectangle(const Point\&, const Size\&) constructor

Construye una nueva instancia del objeto [Rectangle](../) que representa un rectángulo con las coordenadas de su esquina superior izquierda especificadas como una instancia de la clase [Point](../../point/) y su ancho y altura como una instancia de la clase [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Especifica la ubicación de la esquina superior izquierda del rectángulo |
| size | const [Size](../../size/)\& | Especifica el ancho y la altura del rectángulo |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle\_&) constructor

Construye una nueva instancia del objeto [Rectangle](../) que representa el rectángulo equivalente al especificado.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Una instancia de la clase **System::Windows::Forms::Screen::Rectangle_** que especifica la posición y el tamaño del rectángulo que será representado por el objeto que se está construyendo |

## Ver también

* Clase [Rectangle](../)
* Clase [Point](../../point/)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)