---
title: SlideShowType
second_title: Riferimento API Java per Aspose.Slides per Android
description: Impostazioni di base della presentazione.
type: docs
url: /it/com.aspose.slides/slideshowtype/
---
**Ereditarietà:**
java.lang.Object
```
public abstract class SlideShowType
```

Impostazioni di base della presentazione. Gli antenati rappresentano i tipi di presentazione: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Presentata da un relatore (schermo intero) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Visualizzata da un individuo (finestra) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Visualizzata in un chiosco (schermo intero)

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