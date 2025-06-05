---
title: HeaderFooterManager
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve el administrador de HeaderFooter actual. Solo lectura IPresentationHeaderFooterManageraspose.slides/ipresentationheaderfootermanager.
type: docs
weight: 120
url: /es/aspose.slides/presentation/headerfootermanager/
---

## Propiedad Presentation.HeaderFooterManager

Devuelve el administrador de HeaderFooter actual. Solo lectura [`IPresentationHeaderFooterManager`](../../ipresentationheaderfootermanager).

```csharp
public IPresentationHeaderFooterManager HeaderFooterManager { get; }
```

### Ejemplos

El siguiente ejemplo muestra cómo establecer la visibilidad del pie de página dentro de una diapositiva de la presentación de PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("presentation.ppt"))
{
    IBaseSlideHeaderFooterManager headerFooterManager = presentation.Slides[0].HeaderFooterManager;
	// La propiedad IsFooterVisible se utiliza para indicar que un marcador de posición del pie de página de la diapositiva no está presente.
    if (!headerFooterManager.IsFooterVisible)
    {
		// El método SetFooterVisibility se utiliza para hacer visible un marcador de posición del pie de página de la diapositiva.
        headerFooterManager.SetFooterVisibility(true);
    }
	// La propiedad IsSlideNumberVisible se utiliza para indicar que un marcador de posición del número de página de la diapositiva no está presente.
    if (!headerFooterManager.IsSlideNumberVisible)
    {
		// El método SetSlideNumberVisibility se utiliza para hacer visible un marcador de posición del número de página de la diapositiva.
        headerFooterManager.SetSlideNumberVisibility(true);
    }
	// La propiedad IsDateTimeVisible se utiliza para indicar que un marcador de posición de fecha y hora de la diapositiva no está presente.
    if (!headerFooterManager.IsDateTimeVisible)
    {
		// El método SetFooterVisibility se utiliza para hacer visible un marcador de posición de fecha y hora de la diapositiva.
        headerFooterManager.SetDateTimeVisibility(true);
    }
	// El método SetFooterText se utiliza para establecer el texto en el marcador de posición del pie de página de la diapositiva.
    headerFooterManager.SetFooterText("Texto del pie de página");
	// El método SetDateTimeText se utiliza para establecer el texto en el marcador de posición de fecha y hora de la diapositiva.
    headerFooterManager.SetDateTimeText("Texto de fecha y hora");
	presentation.Save("Presentation.ppt",SaveFormat.ppt);
}
```

El siguiente ejemplo muestra cómo establecer la visibilidad de los pies de página hijos dentro de una diapositiva.

```csharp
[C#]
using (Presentation presentation = new Presentation("presentation.ppt"))
{
    IMasterSlideHeaderFooterManager headerFooterManager = presentation.Masters[0].HeaderFooterManager;
	// El método SetFooterAndChildFootersVisibility se utiliza para hacer visibles un pie de página de la diapositiva maestra y todos los marcadores de posición de los pies de página hijos.
    headerFooterManager.SetFooterAndChildFootersVisibility(true);
	// El método SetSlideNumberAndChildSlideNumbersVisibility se utiliza para hacer visibles un número de página de la diapositiva maestra y todos los marcadores de posición de los números de página hijos.
    headerFooterManager.SetSlideNumberAndChildSlideNumbersVisibility(true);
	// El método SetDateTimeAndChildDateTimesVisibility se utiliza para hacer visibles un pie de página de la diapositiva maestra y todos los marcadores de posición de fecha y hora hijos.
    headerFooterManager.SetDateTimeAndChildDateTimesVisibility(true);
	// El método SetFooterAndChildFootersText se utiliza para establecer texto en el pie de página de la diapositiva maestra y todos los marcadores de posición de los pies de página hijos.
    headerFooterManager.SetFooterAndChildFootersText("Texto del pie de página");
	// El método SetDateTimeAndChildDateTimesText se utiliza para establecer texto en la diapositiva maestra y todos los marcadores de posición de fecha y hora hijos.
    headerFooterManager.SetDateTimeAndChildDateTimesText("Texto de fecha y hora");
}
```

### Vea También

* interfaz [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamble [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->