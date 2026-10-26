---
title: PresentedBySpeaker
second_title: Aspose.Slides के लिए Java API संदर्भ
description: स्पीकर द्वारा पूर्ण स्क्रीन पर प्रस्तुत
type: docs
url: /hi/com.aspose.slides/presentedbyspeaker/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

स्पीकर द्वारा प्रस्तुत (पूर्ण स्क्रीन)

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
## कंस्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | PresentedBySpeaker वर्ग का एक नया उदाहरण प्रारंभ करता है। |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


PresentedBySpeaker वर्ग का एक नया उदाहरण प्रारंभ करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```