---
title: ISlideSize
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un tamaño de diapositiva.
type: docs
weight: 6870
url: /es/aspose.slides/islidesize/
---

## Interfaz ISlideSize

Representa un tamaño de diapositiva.

```csharp
public interface ISlideSize
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Orientation](../../aspose.slides/islidesize/orientation) { get; set; } | Devuelve o establece la orientación de la diapositiva. Cambiar este valor intercambiará las dimensiones de la diapositiva. Lectura/escritura [`SlideOrientation`](../slideorientation). |
| [Size](../../aspose.slides/islidesize/size) { get; } | Devuelve el tamaño en puntos. Asignar cualquier valor restablecerá la propiedad [`Type`](./type) a Personalizado y establecerá [`Orientation`](./orientation). Lectura/escritura SizeF. |
| [Type](../../aspose.slides/islidesize/type) { get; } | Devuelve o establece el tipo de tamaño de diapositiva. Asignar cualquier valor excepto Personalizado cambiará [`Size`](./size) en consecuencia, pero mantendrá [`Orientation`](./orientation) intacta. Lectura/escritura [`SlideSizeType`](../slidesizetype). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetSize](../../aspose.slides/islidesize/setsize#setsize)(SlideSizeType, SlideSizeScaleType) | Establece el tipo de tamaño de diapositiva y escala el contenido utilizando el tipo de escala. Asignar cualquier valor excepto Personalizado cambiará [`Size`](./size) en consecuencia, pero mantendrá [`Orientation`](./orientation) intacta. |
| [SetSize](../../aspose.slides/islidesize/setsize#setsize_1)(float, float, SlideSizeScaleType) | Establece el tamaño en puntos y escala el contenido utilizando el tipo de escala. Asignar cualquier valor restablecerá la propiedad [`Type`](./type) a Personalizado y establecerá [`Orientation`](./orientation). |

### Ver También

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->