---
title: SlideShowType
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el tipo de presentación. Representado por los siguientes ancestros de SlideShowTypeaspose.slides/slideshowsettings/slideshowtype BrowsedAtKioskaspose.slides/browsedatkiosk PresentedBySpeakeraspose.slides/presentedbyspeaker y BrowsedByIndividualaspose.slides/browsedbyindividual
type: docs
weight: 70
url: /es/aspose.slides/slideshowsettings/slideshowtype/
---

## Propiedad SlideShowSettings.SlideShowType

Obtiene o establece el tipo de presentación. Representado por los siguientes ancestros `SlideShowType`: [`BrowsedAtKiosk`](../../browsedatkiosk), [`PresentedBySpeaker`](../../presentedbyspeaker) y [`BrowsedByIndividual`](../../browsedbyindividual)

```csharp
public SlideShowType SlideShowType { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    // para establecer el tipo "Navegado en un quiosco (pantalla completa)" 
    pres.SlideShowSettings.SlideShowType = new BrowsedAtKiosk();
    
    // para establecer el tipo "Navegado por un individuo (ventana)"
    pres.SlideShowSettings.SlideShowType = new BrowsedByIndividual();
    
    // para establecer el tipo "Presentado por un orador (pantalla completa)"
    pres.SlideShowSettings.SlideShowType = new PresentedBySpeaker();
}
```

### Véase También

* clase [SlideShowType](../../slideshowtype)
* clase [SlideShowSettings](../../slideshowsettings)
* espacio de nombres [Aspose.Slides](../../slideshowsettings)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->