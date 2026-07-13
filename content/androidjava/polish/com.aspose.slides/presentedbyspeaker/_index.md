---
title: PresentedBySpeaker
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Prezentowane przez prelegenta na pełnym ekranie
type: docs
url: /pl/com.aspose.slides/presentedbyspeaker/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Prezentowane przez prelegenta (pełny ekran)

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

| Konstruktor | Opis |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Inicjalizuje nową instancję klasy PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Inicjalizuje nową instancję klasy PresentedBySpeaker.

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