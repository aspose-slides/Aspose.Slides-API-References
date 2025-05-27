---
title: IPortion
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una porción de texto dentro de un párrafo de texto.
type: docs
weight: 6500
url: /es/aspose.slides/iportion/
---

## Interfaz IPortion

Representa una porción de texto dentro de un párrafo de texto.

```csharp
public interface IPortion : ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISlideComponent](../../aspose.slides/iportion/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [Field](../../aspose.slides/iportion/field) { get; } | Retorna un campo de esta porción. Solo lectura [`IField`](../ifield). |
| [PortionFormat](../../aspose.slides/iportion/portionformat) { get; } | Retorna el objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin herencia aplicada. Solo lectura [`IPortionFormat`](../iportionformat). |
| [Text](../../aspose.slides/iportion/text) { get; set; } | Obtiene o establece el texto plano de una porción. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddField](../../aspose.slides/iportion/addfield#addfield)(IFieldType) | Convierte esta porción en un campo actualizado automáticamente. |
| [AddField](../../aspose.slides/iportion/addfield#addfield_1)(string) | Convierte esta porción en un campo actualizado automáticamente. |
| [GetCoordinates](../../aspose.slides/iportion/getcoordinates)() | Obtiene las coordenadas del comienzo de la porción. La coordenada X del punto representa el comienzo de la porción desde el primer carácter incluyendo el margen izquierdo. La coordenada Y incluye el margen superior. |
| [GetRect](../../aspose.slides/iportion/getrect)() | Obtiene las coordenadas del rectángulo que limita la porción. El rectángulo incluye todas las líneas de texto en la porción, incluyendo las vacías. |
| [RemoveField](../../aspose.slides/iportion/removefield)() | Convierte esta porción de campo en una porción simple. |

### Vea También

* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->