---
title: PresentedBySpeaker
second_title: Aspose.Slides för Android via Java API-referens
description: Presenteras av en talare i helskärm
type: docs
url: /sv/com.aspose.slides/presentedbyspeaker/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Presenteras av en talare (fullskärm)

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

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Initierar en ny instans av klassen PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

Initierar en ny instans av klassen PresentedBySpeaker.

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
