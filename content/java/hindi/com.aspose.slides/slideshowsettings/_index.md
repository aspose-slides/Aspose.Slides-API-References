---
title: SlideShowSettings
second_title: Aspose.Slides for Java API संदर्भ
description: प्रेजेंटेशन के स्लाइड शो सेटिंग्स को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/slideshowsettings/
---
**Inheritance:**
java.lang.Object
```
public class SlideShowSettings
```

प्रेजेंटेशन के स्लाइड शो सेटिंग्स को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | स्लाइड शो प्रकार को प्राप्त करता है या सेट करता है। |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | स्लाइड शो प्रकार को प्राप्त करता है या सेट करता है। |
| [getLoop()](#getLoop--) | स्लाइड शो लूप |
| [setLoop(boolean value)](#setLoop-boolean-) | स्लाइड शो लूप |
| [getShowNarration()](#getShowNarration--) | स्लाइड शो में नैरेशन दिखाएँ |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | स्लाइड शो में नैरेशन दिखाएँ |
| [getShowAnimation()](#getShowAnimation--) | स्लाइड शो में एनीमेशन दिखाएँ |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | स्लाइड शो में एनीमेशन दिखाएँ |
| [getPenColor()](#getPenColor--) | स्लाइड शो के लिए पेन रंग |
| [getSlides()](#getSlides--) | स्लाइड्स की सीमा |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | स्लाइड्स की सीमा |
| [getUseTimings()](#getUseTimings--) | स्लाइड शो में टाइमिंग्स का उपयोग करें |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | स्लाइड शो में टाइमिंग्स का उपयोग करें |
| [getShowMediaControls()](#getShowMediaControls--) | मीडिया कंट्रोल्स दिखाएँ |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | मीडिया कंट्रोल्स दिखाएँ |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

स्लाइड शो प्रकार को प्राप्त करता है या सेट करता है। नीचे दिए गए SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) पूर्वज: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) और [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" प्रकार सेट करने के लिए
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" प्रकार सेट करने के लिए
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" प्रकार सेट करने के लिए
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[SlideShowType](../../com.aspose.slides/slideshowtype)

### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

स्लाइड शो प्रकार को प्राप्त करता है या सेट करता है। नीचे दिए गए SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) पूर्वज: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) और [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" प्रकार सेट करने के लिए
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" प्रकार सेट करने के लिए
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" प्रकार सेट करने के लिए
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

स्लाइड शो लूप

**वापसी:**
boolean

### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

स्लाइड शो लूप

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

स्लाइड शो में नैरेशन दिखाएँ

**वापसी:**
boolean

### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

स्लाइड शो में नैरेशन दिखाएँ

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

स्लाइड शो में एनीमेशन दिखाएँ

**वापसी:**
boolean

### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

स्लाइड शो में एनीमेशन दिखाएँ

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

स्लाइड शो के लिए पेन रंग

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

स्लाइड्स की सीमा

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[SlidesRange](../../com.aspose.slides/slidesrange)

### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

स्लाइड्स की सीमा

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

स्लाइड शो में टाइमिंग्स का उपयोग करें

**वापसी:**
boolean

### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

स्लाइड शो में टाइमिंग्स का उपयोग करें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

मीडिया कंट्रोल्स दिखाएँ

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
boolean

### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

मीडिया कंट्रोल्स दिखाएँ

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |