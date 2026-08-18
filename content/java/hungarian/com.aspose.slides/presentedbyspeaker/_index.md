---
title: PresentedBySpeaker
second_title: Aspose.Slides Java API referencia
description: Előadó által teljes képernyőn bemutatva
type: docs
url: /hu/com.aspose.slides/presentedbyspeaker/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Előadó által bemutatott (teljes képernyő)

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Inicializál egy új példányt a PresentedBySpeaker osztályból. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Inicializál egy új példányt a PresentedBySpeaker osztályból.

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