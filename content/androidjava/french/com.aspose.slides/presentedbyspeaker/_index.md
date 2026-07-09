---
title: PresentedBySpeaker
second_title: Référence de l'API Java Aspose.Slides pour Android
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
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Initializes a new instance of the PresentedBySpeaker class. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()


Initializes a new instance of the PresentedBySpeaker class.

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