---
title: SlideShowType
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Βασικές ρυθμίσεις παρουσίασης διαφανειών.
type: docs
url: /el/com.aspose.slides/slideshowtype/
---
**Κληρονομικότητα:**
java.lang.Object
```
public abstract class SlideShowType
```

Βασικές ρυθμίσεις παρουσίασης διαφανειών. Οι προγόνοι αντιπροσωπεύουν τύπους της παρουσίασης διαφανειών: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Παρουσιάζεται από ομιλητή (πλήρης οθόνη) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Περιηγείται από άτομο (παράθυρο) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Περιηγείται σε περίπτερο (πλήρης οθόνη)

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