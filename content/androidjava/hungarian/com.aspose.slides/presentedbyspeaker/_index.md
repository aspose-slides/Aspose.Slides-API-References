---
title: PresentedBySpeaker
second_title: Aspose.Slides Androidra Java API hivatkozáshoz
description: Előadva egy előadó által teljes képernyőn
type: docs
url: /hu/com.aspose.slides/presentedbyspeaker/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Előadva egy előadó által (teljes képernyő)

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
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Új példányt hoz létre a PresentedBySpeaker osztályból. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

Új példányt hoz létre a PresentedBySpeaker osztályból.

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
