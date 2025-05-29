---
title: IPoint
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa el punto de animación.
type: docs
weight: 460
url: /es/aspose.slides.animation/ipoint/
---

## Interfaz IPoint

Representa el punto de animación.

```csharp
public interface IPoint
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Formula](../../aspose.slides.animation/ipoint/formula) { get; set; } | Las fórmulas dentro de los valores, desde, hasta, por los atributos pueden estar compuestas de los siguientes: Operadores aritméticos estándar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constantes: ‘pi’ ‘e’ Operadores condicionales: ‘abs’, ‘min’, ‘max’, ‘?’ (si) Operadores de comparación: '==', '&gt;=', '', '!=', '!' Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Logaritmo natural ‘ln()’ Referencias a propiedades (propiedades soportadas por el host) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Leer/escribir Cadena. |
| [Time](../../aspose.slides.animation/ipoint/time) { get; set; } | Representa el valor del tiempo. Leer/escribir Solo. |
| [Value](../../aspose.slides.animation/ipoint/value) { get; set; } | Representa el valor del punto. Solo: bool, ColorFormat, float, int, string. Leer/escribir Objeto. |

### Ver También

* namespace [Aspose.Slides.Animation](../../aspose.slides.animation)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->