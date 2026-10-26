---
title: SlideShowType
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Configuración base de la presentación de diapositivas.
type: docs
url: /es/com.aspose.slides/slideshowtype/
---
**Herencia:**
java.lang.Object
```
public abstract class SlideShowType
```

Configuración base de la presentación de diapositivas. Los ancestros representan tipos de la presentación de diapositivas: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Presentado por un orador (pantalla completa) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Navegado por un individuo (ventana) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Navegado en un quiosco (pantalla completa)

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