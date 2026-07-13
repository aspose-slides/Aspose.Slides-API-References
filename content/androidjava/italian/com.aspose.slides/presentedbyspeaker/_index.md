---
title: PresentedBySpeaker
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Presentato da un relatore a schermo intero
type: docs
url: /it/com.aspose.slides/presentedbyspeaker/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Presentato da un relatore (schermo intero)

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Inizializza una nuova istanza della classe PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Inizializza una nuova istanza della classe PresentedBySpeaker.

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