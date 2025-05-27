---
title: PresentationFactory
second_title: Referencia de API de Aspose.Slides para .NET
description: Permite crear presentaciones a través de la interfaz COM
type: docs
weight: 9330
url: /es/aspose.slides/presentationfactory/
---

## Clase PresentationFactory

Permite crear presentaciones a través de la interfaz COM

```csharp
public class PresentationFactory : IPresentationFactory
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentationFactory](presentationfactory)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Instance](../../aspose.slides/presentationfactory/instance) { get; } | Instancia estática de la fábrica de presentaciones. Solo lectura [`PresentationFactory`](../presentationfactory). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreatePresentation](../../aspose.slides/presentationfactory/createpresentation#createpresentation)() | Crea una nueva presentación. |
| [CreatePresentation](../../aspose.slides/presentationfactory/createpresentation#createpresentation_1)(ILoadOptions) | Crea una nueva presentación con opciones de carga adicionales |
| [GetPresentationInfo](../../aspose.slides/presentationfactory/getpresentationinfo#getpresentationinfo)(Stream) | Crea un nuevo objeto PresentationInfo a partir de un stream y vincula la presentación a él. Obtiene información sobre la presentación en el stream especificado. |
| [GetPresentationInfo](../../aspose.slides/presentationfactory/getpresentationinfo#getpresentationinfo_1)(string) | Crea un nuevo objeto PresentationInfo a partir de un archivo y vincula la presentación a él. |
| [GetPresentationText](../../aspose.slides/presentationfactory/getpresentationtext#getpresentationtext)(Stream, TextExtractionArrangingMode) | Recupera el texto en bruto de las diapositivas |
| [GetPresentationText](../../aspose.slides/presentationfactory/getpresentationtext#getpresentationtext_2)(string, TextExtractionArrangingMode) | Recupera el texto en bruto de las diapositivas |
| [GetPresentationText](../../aspose.slides/presentationfactory/getpresentationtext#getpresentationtext_1)(Stream, TextExtractionArrangingMode, ILoadOptions) | Recupera el texto en bruto de las diapositivas |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation#readpresentation)(byte[]) | Lee una presentación existente desde un array |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation#readpresentation_2)(Stream) | Lee una presentación existente desde un stream |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation#readpresentation_4)(string) | Lee una presentación existente desde un archivo |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation#readpresentation_1)(byte[], ILoadOptions) | Lee una presentación existente desde un array con opciones de carga adicionales |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation#readpresentation_3)(Stream, ILoadOptions) | Lee una presentación existente desde un stream con opciones de carga adicionales |
| [ReadPresentation](../../aspose.slides/presentationfactory/readpresentation#readpresentation_5)(string, ILoadOptions) | Lee una presentación existente desde un stream con opciones de carga adicionales |

### Ejemplos

El siguiente ejemplo muestra cómo verificar el formato de una presentación.

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
Console.WriteLine(info.LoadFormat); // PPTX
IPresentationInfo info2 = PresentationFactory.Instance.GetPresentationInfo("pres.ppt");
Console.WriteLine(info2.LoadFormat); // PPT
IPresentationInfo info3 = PresentationFactory.Instance.GetPresentationInfo("pres.odp");
Console.WriteLine(info3.LoadFormat); // ODP
```

El siguiente ejemplo muestra cómo obtener las propiedades de una presentación.

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
Console.WriteLine(props.CreatedTime);
Console.WriteLine(props.Subject);
Console.WriteLine(props.Title);
// ..
```

El siguiente ejemplo muestra cómo actualizar las propiedades de una presentación.

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
props.Title = "Mi título";
info.UpdateDocumentProperties(props);
```

### Véase también

* interfaz [IPresentationFactory](../ipresentationfactory)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->