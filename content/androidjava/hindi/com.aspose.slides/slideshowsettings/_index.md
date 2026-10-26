---
title: SlideShowSettings
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रस्तुति के लिए स्लाइड शो सेटिंग्स का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/slideshowsettings/
---
**विरासत:**
java.lang.Object
```
public class SlideShowSettings
```

प्रस्तुति के लिए स्लाइड शो सेटिंग्स का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Gets or sets the slide show type. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Gets or sets the slide show type. |
| [getLoop()](#getLoop--) | Loop Slide Show |
| [setLoop(boolean value)](#setLoop-boolean-) | Loop Slide Show |
| [getShowNarration()](#getShowNarration--) | Show Narration in Slide Show |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Show Narration in Slide Show |
| [getShowAnimation()](#getShowAnimation--) | Show Animation in Slide Show |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Show Animation in Slide Show |
| [getPenColor()](#getPenColor--) | Pen Color for Slide Show |
| [getSlides()](#getSlides--) | Slides range |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Slides range |
| [getUseTimings()](#getUseTimings--) | Use Timings in Slide Show |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Use Timings in Slide Show |
| [getShowMediaControls()](#getShowMediaControls--) | Show Media Controls |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Show Media Controls |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


स्लाइड शो प्रकार को प्राप्त करता है या सेट करता है। निम्नलिखित SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) पूर्वज: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) और [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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


स्लाइड शो प्रकार को प्राप्त करता है या सेट करता है। निम्नलिखित SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) पूर्वज: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) और [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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


लूप स्लाइड शो

**वापसी:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


लूप स्लाइड शो

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


स्लाइड्स रेंज

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


स्लाइड्स रेंज

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


मीडिया नियंत्रण दिखाएँ

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


मीडिया नियंत्रण दिखाएँ

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |