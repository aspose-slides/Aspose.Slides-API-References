---
title: PresentedBySpeaker
second_title: Aspose.Slides pro Java – referenční příručka API
description: Prezentováno přednášejícím na celou obrazovku
type: docs
url: /cs/com.aspose.slides/presentedbyspeaker/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Prezentováno přednášejícím (na celou obrazovku)

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
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Inicializuje novou instanci třídy PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

Inicializuje novou instanci třídy PresentedBySpeaker.

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