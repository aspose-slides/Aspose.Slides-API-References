---
title: SlideShowType
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: बेस स्लाइड शो सेटिंग्स।
type: docs
url: /hi/com.aspose.slides/slideshowtype/
---
**विरासत:**
java.lang.Object
```
public abstract class SlideShowType
```

बेस स्लाइड शो सेटिंग्स। पूर्वज स्लाइड शो के प्रकार का प्रतिनिधित्व करते हैं: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) एक स्पीकर द्वारा प्रस्तुत (पूर्ण स्क्रीन) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) व्यक्ति द्वारा ब्राउज़ किया (विंडो) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) कियोस्क पर ब्राउज़ किया (पूर्ण स्क्रीन)

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