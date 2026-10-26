---
title: BrowsedByIndividual
second_title: Aspose.Slides for Java API संदर्भ
description: व्यक्तिगत विंडो द्वारा ब्राउज़ किया गया
type: docs
url: /hi/com.aspose.slides/browsedbyindividual/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

व्यक्ति द्वारा ब्राउज़ किया गया (विंडो)

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | BrowsedByIndividual क्लास का नया उदाहरण इनिशियलाइज़ करता है। |
## मेथड

| मेथड | विवरण |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | विंडो में स्क्रॉल बार दिखाएँ |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | विंडो में स्क्रॉल बार दिखाएँ |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

BrowsedByIndividual क्लास का नया उदाहरण इनिशियलाइज़ करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```

विंडो में स्क्रॉल बार दिखाएँ

**रिटर्न:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

विंडो में स्क्रॉल बार दिखाएँ

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |