---
title: SlideShowType
second_title: Riferimento API Aspose.Slides per Java
description: Impostazioni di base della presentazione.
type: docs
url: /it/com.aspose.slides/slideshowtype/
---
**Ereditarietà:**
java.lang.Object
```
public abstract class SlideShowType
```

Impostazioni di base della presentazione. Gli antenati rappresentano i tipi di presentazione: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Presentato da un relatore (schermo intero) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Visualizzato da un individuo (finestra) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Visualizzato in un chiosco (schermo intero)

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