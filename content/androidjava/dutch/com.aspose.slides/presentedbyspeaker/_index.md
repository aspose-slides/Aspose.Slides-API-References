---
title: PresentedBySpeaker
second_title: Aspose.Slides voor Android via Java API-referentie
description: Voorstelling door een spreker in volledig scherm
type: docs
url: /nl/com.aspose.slides/presentedbyspeaker/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Voorstelling door een spreker (volledig scherm)

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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Initialiseert een nieuw exemplaar van de PresentedBySpeaker-klasse. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Initialiseert een nieuw exemplaar van de PresentedBySpeaker-klasse.

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