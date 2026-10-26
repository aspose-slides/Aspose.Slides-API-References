---
title: SlideShowType
second_title: Aspose.Slides para Android via Referência da API Java
description: Configurações básicas de apresentação de slides.
type: docs
url: /pt/com.aspose.slides/slideshowtype/
---
**Herança:**
java.lang.Object
```
public abstract class SlideShowType
```

Configurações básicas de apresentação de slides. Os ancestrais representam tipos de apresentação de slides: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Apresentado por um palestrante (tela cheia) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Navegado por um indivíduo (janela) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Navegado em um quiosque (tela cheia)

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