---
title: SlideSize
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un tamaño de diapositiva.
type: docs
weight: 10190
url: /es/aspose.slides/slidesize/
---

## Clase SlideSize

Representa un tamaño de diapositiva.

```csharp
public class SlideSize : DomObject<Presentation>, ISlideSize
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Orientation](../../aspose.slides/slidesize/orientation) { get; set; } | Devuelve o establece la orientación de la diapositiva. Cambiar este valor intercambiará las dimensiones de la diapositiva. Lectura/escritura [`SlideOrientation`](../slideorientation). |
| [Size](../../aspose.slides/slidesize/size) { get; } | Devuelve o establece el tamaño en puntos. Asignar cualquier valor restablecerá la propiedad [`Type`](./type) a Personalizado y establecerá [`Orientation`](./orientation). Lectura/escritura SizeF. |
| [Type](../../aspose.slides/slidesize/type) { get; } | Devuelve o establece el tipo de tamaño de diapositiva. Asignar cualquier valor excepto Personalizado cambiará [`Size`](./size) en consecuencia, pero mantendrá intacta [`Orientation`](./orientation). Lectura/escritura [`SlideSizeType`](../slidesizetype). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetSize](../../aspose.slides/slidesize/setsize#setsize)(SlideSizeType, SlideSizeScaleType) | Establece el tipo de tamaño de diapositiva y escala el contenido utilizando el tipo de escala. Asignar cualquier valor excepto Personalizado cambiará [`Size`](./size) en consecuencia, pero mantendrá intacta [`Orientation`](./orientation). |
| [SetSize](../../aspose.slides/slidesize/setsize#setsize_1)(float, float, SlideSizeScaleType) | Establece el tamaño en puntos y escala el contenido utilizando el tipo de escala. Asignar cualquier valor restablecerá la propiedad [`Type`](./type) a Personalizado y establecerá [`Orientation`](./orientation). |

### Véase también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Presentation](../presentation)
* interfaz [ISlideSize](../islidesize)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->