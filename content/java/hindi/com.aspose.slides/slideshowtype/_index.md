---
title: SlideShowType
second_title: Aspose.Slides for Java API संदर्भ
description: बेस स्लाइड शो सेटिंग्स।
type: docs
url: /hi/com.aspose.slides/slideshowtype/
---
**विरासत:**
java.lang.Object
```
public abstract class SlideShowType
```

Base slide शो सेटिंग्स। पूर्वज स्लाइड शो के प्रकारों का प्रतिनिधित्व करते हैं: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) स्पीकर द्वारा प्रस्तुत (पूर्ण स्क्रीन) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) व्यक्तिगत द्वारा ब्राउज़ किया गया (विंडो) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) कियोस्क पर ब्राउज़ किया गया (पूर्ण स्क्रीन)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("PresentedBySpeaker.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("BrowsedByIndividual.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("BrowsedAtKiosk.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
