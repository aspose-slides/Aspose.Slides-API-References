---
title: IPortion
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una porción de texto dentro de un párrafo de texto.
type: docs
weight: 6140
url: /es/net/aspose.slides/iportion/
---
## IPortion interface

Representa una porción de texto dentro de un párrafo de texto.

```csharp
public interface IPortion : ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISlideComponent](../../aspose.slides/iportion/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura[`ISlideComponent`](../islidecomponent) . |
| [Field](../../aspose.slides/iportion/field) { get; } | Devuelve un campo de esta porción. Solo lectura[`IField`](../ifield) . |
| [PortionFormat](../../aspose.slides/iportion/portionformat) { get; } | Devuelve el objeto de formato que contiene propiedades de formato definidas explícitamente de la parte del texto sin aplicar herencia. Solo lectura[`IPortionFormat`](../iportionformat) . |
| [Text](../../aspose.slides/iportion/text) { get; set; } | Obtiene o establece el texto sin formato de una porción. Lectura/escrituraString . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddField](../../aspose.slides/iportion/addfield#addfield)(IFieldType) | Convierte esta porción al campo actualizado automáticamente. |
| [AddField](../../aspose.slides/iportion/addfield#addfield_1)(string) | Convierte esta porción al campo actualizado automáticamente. |
| [GetCoordinates](../../aspose.slides/iportion/getcoordinates)() | Obtiene las coordenadas del inicio de la porción. La coordenada X del punto representa la porción que comienza desde el primer carácter, incluido el rumbo del lado izquierdo. La coordenada Y incluye el rumbo del lado superior. |
| [GetRect](../../aspose.slides/iportion/getrect)() | Obtiene las coordenadas del rect que limita la porción. El rect incluye todas las líneas de texto en parte, incluidas las vacías. |
| [RemoveField](../../aspose.slides/iportion/removefield)() | Convierte esta porción de campo a la porción simple. |

### Ver también

* interface [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->