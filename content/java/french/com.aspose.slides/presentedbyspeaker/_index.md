---
title: PresentedBySpeaker
second_title: Aspose.Slides pour la référence API Java
description: Présenté par un intervenant en plein écran
type: docs
url: /fr/com.aspose.slides/presentedbyspeaker/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Présenté par un intervenant (plein écran)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Initialise une nouvelle instance de la classe PresentedBySpeaker. |

### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

Initialise une nouvelle instance de la classe PresentedBySpeaker.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```