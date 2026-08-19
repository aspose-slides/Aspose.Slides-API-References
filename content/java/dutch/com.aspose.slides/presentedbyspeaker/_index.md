---
title: PresentedBySpeaker
second_title: Aspose.Slides voor Java API-referentie
description: Gepresenteerd door een spreker op volledig scherm
type: docs
url: /nl/com.aspose.slides/presentedbyspeaker/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Gepresenteerd door een spreker (volledig scherm)

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

| Constructor | Beschrijving |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Initialiseert een nieuwe instantie van de PresentedBySpeaker class. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

Initialiseert een nieuwe instantie van de PresentedBySpeaker class.

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