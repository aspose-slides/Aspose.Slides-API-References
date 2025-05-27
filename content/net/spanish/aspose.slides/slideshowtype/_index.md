---
title: SlideShowType
second_title: Referencia de la API de Aspose.Slides para .NET
description: Configuraciones básicas de presentación de diapositivas. Los ancestros representan tipos de la presentación: PresentadoPorOrador./presentedbyspeaker Presentado por un orador pantalla completa NavegadoPorIndividuo./browsedbyindividual Navegado por un individuo ventana NavegadoEnKiosco./browsedatkiosk Navegado en un kiosco pantalla completa
type: docs
weight: 10180
url: /es/aspose.slides/slideshowtype/
---

## Clase SlideShowType

Configuraciones básicas de presentación de diapositivas. Los ancestros representan tipos de la presentación: [`PresentedBySpeaker`](../presentedbyspeaker) Presentado por un orador (pantalla completa) [`BrowsedByIndividual`](../browsedbyindividual) Navegado por un individuo (ventana) [`BrowsedAtKiosk`](../browsedatkiosk) Navegado en un kiosco (pantalla completa)

```csharp
public abstract class SlideShowType
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.SlideShowSettings.SlideShowType = new PresentedBySpeaker();
    pres.Save("PresentedBySpeaker.pptx", SaveFormat.Pptx);

    pres.SlideShowSettings.SlideShowType = new BrowsedByIndividual();
    pres.Save("BrowsedByIndividual.pptx", SaveFormat.Pptx);

    pres.SlideShowSettings.SlideShowType = new BrowsedAtKiosk();
    pres.Save("BrowsedAtKiosk.pptx", SaveFormat.Pptx);
}
```

### Ver También

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->