---
title: SlideShowType
second_title: Aspose.Slides pour Android via la référence API Java
description: Paramètres de base du diaporama.
type: docs
url: /fr/com.aspose.slides/slideshowtype/
---
**Héritage:**
java.lang.Object
```
public abstract class SlideShowType
```

Paramètres de base du diaporama. Les ancêtres représentent les types du diaporama : [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Présenté par un présentateur (plein écran) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Consulté par un individu (fenêtre) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Consulté sur un kiosque (plein écran)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("PresentedBySpeaker.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("BrowsedByIndividual.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("BrowsedAtKiosk.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```