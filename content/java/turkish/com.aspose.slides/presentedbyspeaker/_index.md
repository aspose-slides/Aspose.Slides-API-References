---
title: PresentedBySpeaker
second_title: Aspose.Slides için Java API Referansı
description: Tam ekranda bir konuşmacı tarafından sunulur
type: docs
url: /tr/com.aspose.slides/presentedbyspeaker/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Bir konuşmacı tarafından sunulan (tam ekran)

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

## Yapıcılar

| Constructor | Description |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | PresentedBySpeaker sınıfının yeni bir örneğini başlatır. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

PresentedBySpeaker sınıfının yeni bir örneğini başlatır.

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