---
title: IPortionFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de la parte de texto. A diferencia deIPortionFormatEffectiveData./iportionformateffectivedata  todas las propiedades de esta clase se pueden escribir.
type: docs
weight: 6170
url: /es/net/aspose.slides/iportionformat/
---
## IPortionFormat interface

Esta clase contiene las propiedades de formato de la parte de texto. A diferencia de[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , todas las propiedades de esta clase se pueden escribir.

```csharp
public interface IPortionFormat : IBasePortionFormat, IHyperlinkContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIBasePortionFormat](../../aspose.slides/iportionformat/asibaseportionformat) { get; } | Devuelve la interfaz IBasePortionFormat. Solo lectura[`IBasePortionFormat`](../ibaseportionformat) . |
| [AsIHyperlinkContainer](../../aspose.slides/iportionformat/asihyperlinkcontainer) { get; } | Permite obtener la interfaz base IHyperlinkContainer. Solo lectura[`IHyperlinkContainer`](../ihyperlinkcontainer) . |
| [BookmarkId](../../aspose.slides/iportionformat/bookmarkid) { get; set; } | Devuelve o establece el identificador de marcador. Lectura/escrituraString . |
| [SmartTagClean](../../aspose.slides/iportionformat/smarttagclean) { get; set; } | Determina si se debe limpiar la etiqueta inteligente. No se aplica herencia. Lectura/escrituraBoolean . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/iportionformat/geteffective)() | Obtiene datos de formato de porción efectivo con la herencia aplicada. |

### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de la porción de texto definidas para la porción en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "indefinido".

Para obtener los valores de parámetros de formato efectivos, incluidos los heredados, debe usar[`GetEffective`](./geteffective) método que devuelve un[`IPortionFormatEffectiveData`](../iportionformateffectivedata) instancia.

### Ver también

* interface [IBasePortionFormat](../ibaseportionformat)
* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->