---
title: NormalViewProperties
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa las propiedades de la vista normal. La vista normal consiste en tres regiones de contenido la diapositiva en sí, una región de contenido lateral y una región de contenido inferior.
type: docs
weight: 8840
url: /es/aspose.slides/normalviewproperties/
---

## Clase NormalViewProperties

Representa las propiedades de la vista normal. La vista normal consiste en tres regiones de contenido: la diapositiva en sí, una región de contenido lateral y una región de contenido inferior.

```csharp
public class NormalViewProperties : INormalViewProperties
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HorizontalBarState](../../aspose.slides/normalviewproperties/horizontalbarstate) { get; set; } | Especifica el estado en el que debe mostrarse la barra divisoria horizontal. Una barra divisoria horizontal separa la diapositiva de la región de contenido debajo de la diapositiva. |
| [PreferSingleView](../../aspose.slides/normalviewproperties/prefersingleview) { get; set; } | Especifica si el usuario prefiere ver una región de contenido de ventana completa en lugar de la vista normal estándar con tres regiones de contenido. Si está habilitado, la aplicación puede optar por mostrar una de las regiones de contenido en toda la ventana. Booleano de lectura/escritura. |
| [RestoredLeft](../../aspose.slides/normalviewproperties/restoredleft) { get; } | Este elemento especifica el tamaño de la región de contenido lateral de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). Solo de lectura [`INormalViewRestoredProperties`](../inormalviewrestoredproperties). |
| [RestoredTop](../../aspose.slides/normalviewproperties/restoredtop) { get; } | Este elemento especifica el tamaño de la región superior de la diapositiva de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). Solo de lectura [`INormalViewRestoredProperties`](../inormalviewrestoredproperties). |
| [ShowOutlineIcons](../../aspose.slides/normalviewproperties/showoutlineicons) { get; set; } | Especifica si la aplicación debe mostrar íconos al mostrar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. Booleano de lectura/escritura. |
| [SnapVerticalSplitter](../../aspose.slides/normalviewproperties/snapverticalsplitter) { get; set; } | Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es suficientemente pequeña. Booleano de lectura/escritura. |
| [VerticalBarState](../../aspose.slides/normalviewproperties/verticalbarstate) { get; set; } | Especifica el estado en el que debe mostrarse la barra divisoria vertical. Una barra divisoria vertical separa la diapositiva de la región de contenido lateral. |

### Ejemplos

El siguiente ejemplo muestra cómo configurar las propiedades de ViewProperties.NormalViewProperties de una presentación de PowerPoint.

```csharp
[C#]
//Instanciar un objeto de presentación que representa un archivo de presentación
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.ViewProperties.NormalViewProperties.HorizontalBarState = SplitterBarStateType.Restored;
    pres.ViewProperties.NormalViewProperties.VerticalBarState = SplitterBarStateType.Maximized;
    pres.ViewProperties.NormalViewProperties.RestoredTop.AutoAdjust = true;
    pres.ViewProperties.NormalViewProperties.RestoredTop.DimensionSize = 80;
    pres.ViewProperties.NormalViewProperties.ShowOutlineIcons = true;
    pres.Save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [INormalViewProperties](../inormalviewproperties)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->