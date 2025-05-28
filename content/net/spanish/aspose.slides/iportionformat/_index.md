---
title: IPortionFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de porción de texto. A diferencia de IPortionFormatEffectiveData, todas las propiedades de esta clase son escribibles.
type: docs
weight: 6530
url: /es/aspose.slides/iportionformat/
---

## Interfaz IPortionFormat

Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas las propiedades de esta clase son escribibles.

```csharp
public interface IPortionFormat : IBasePortionFormat, IHyperlinkContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIBasePortionFormat](../../aspose.slides/iportionformat/asibaseportionformat) { get; } | Devuelve la interfaz IBasePortionFormat. Solo lectura [`IBasePortionFormat`](../ibaseportionformat). |
| [AsIHyperlinkContainer](../../aspose.slides/iportionformat/asihyperlinkcontainer) { get; } | Permite obtener la interfaz base IHyperlinkContainer. Solo lectura [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [BookmarkId](../../aspose.slides/iportionformat/bookmarkid) { get; set; } | Devuelve o establece el identificador del marcador. Lectura/escritura String. |
| [SmartTagClean](../../aspose.slides/iportionformat/smarttagclean) { get; set; } | Determina si la etiqueta inteligente debe ser limpiada. No se aplica herencia. Lectura/escritura Boolean. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/iportionformat/geteffective)() | Obtiene los datos de formato de porción efectivos con la herencia aplicada. |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de porción de texto definidas para la porción particular. Esto significa que no se aplica la herencia al obtener valores, por lo que en la mayoría de los casos obtendrás valores que significan "indefinido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, necesitas usar el método [`GetEffective`](./geteffective) que devuelve una instancia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Véase También

* interfaz [IBasePortionFormat](../ibaseportionformat)
* interfaz [IHyperlinkContainer](../ihyperlinkcontainer)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->