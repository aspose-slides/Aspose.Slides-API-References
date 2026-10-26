---
title: BrowsedByIndividual
second_title: Aspose.Slides for Android द्वारा Java API संदर्भ
description: व्यक्तिगत द्वारा ब्राउज़ किया गया विंडो
type: docs
url: /hi/com.aspose.slides/browsedbyindividual/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

व्यक्तिगत द्वारा ब्राउज़ किया गया (विंडो)

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
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | BrowsedByIndividual वर्ग का एक नया उदाहरण आरंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | विंडो में स्क्रॉल बार दिखाएँ |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | विंडो में स्क्रॉल बार दिखाएँ |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


BrowsedByIndividual वर्ग का एक नया उदाहरण आरंभ करता है।

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

**वापसी:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


विंदो में स्क्रॉल बार दिखाएँ

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |