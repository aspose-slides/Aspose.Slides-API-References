---
title: Point
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un punto de animación.
type: docs
weight: 640
url: /es/aspose.slides.animation/point/
---

## Clase Point

Representa un punto de animación.

```csharp
public class Point : IPoint
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Point](point#constructor)() | Constructor predeterminado. |
| [Point](point#constructor_1)(float, object, string) | Crea un punto de animación con tiempo, valor y fórmula. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Formula](../../aspose.slides.animation/point/formula) { get; set; } | Las fórmulas dentro de los valores, atributos from, to, by pueden consistir en estos: Operadores aritméticos estándar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constantes: ‘pi’ ‘e’ Operadores condicionales: ‘abs’, ‘min’, ‘max’, ‘?’ (si) Operadores de comparación: '==', '&gt;=', '', '!=', '!' Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Logaritmo natural ‘ln()’ Referencias de propiedad (propiedades soportadas por el anfitrión) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Leer/escribir String. |
| [Time](../../aspose.slides.animation/point/time) { get; set; } | Representa el valor del tiempo. Leer/escribir Single. |
| [Value](../../aspose.slides.animation/point/value) { get; set; } | Representa el valor del punto. Solo: bool, ColorFormat, float, int, string. Leer/escribir Object. |

### Véase También

* interfaz [IPoint](../ipoint)
* espacio de nombres [Aspose.Slides.Animation](../../aspose.slides.animation)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->