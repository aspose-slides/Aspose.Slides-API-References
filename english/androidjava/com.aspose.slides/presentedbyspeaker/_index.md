---
title: PresentedBySpeaker
second_title: Aspose.Slides for Android via Java API Reference
description:  Presented by a speaker full screen
type: docs
weight: 448
url: /androidjava/com.aspose.slides/presentedbyspeaker/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Presented by a speaker (full screen)

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
```


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

