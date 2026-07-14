---
title: HandoutLayoutingOptions
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: निर्यात के लिए हैंडआउट प्रस्तुति लेआउट मोड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/handoutlayoutingoptions/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

निर्यात के लिए हैंडआउट प्रस्तुति लेआउट मोड का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | डिफ़ॉल्ट मानों को प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getHandout()](#getHandout--) | यह निर्दिष्ट करता है कि कितनी स्लाइड्स और किस क्रम में पृष्ठ [HandoutType](../../com.aspose.slides/handouttype) पर रखी जाएँगी। |
| [setHandout(int value)](#setHandout-int-) | यह निर्दिष्ट करता है कि कितनी स्लाइड्स और किस क्रम में पृष्ठ [HandoutType](../../com.aspose.slides/handouttype) पर रखी जाएँगी। |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबरों को प्रिंट किया जाए या नहीं। |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबरों को प्रिंट किया जाए या नहीं। |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड्स के चारों ओर फ्रेम खींचा जाए या नहीं। |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड्स के चारों ओर फ्रेम खींचा जाए या नहीं। |
| [getPrintComments()](#getPrintComments--) | यह निर्दिष्ट करता है कि स्लाइड्स पर टिप्पणी दिखाएँ या न दिखाएँ |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | यह निर्दिष्ट करता है कि स्लाइड्स पर टिप्पणी दिखाएँ या न दिखाएँ |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```

डिफ़ॉल्ट मानों को प्रारंभ करता है।

### getHandout() {#getHandout--}
```
public final int getHandout()
```

यह निर्दिष्ट करता है कि कितनी स्लाइड्स और किस क्रम में पृष्ठ [HandoutType](../../com.aspose.slides/handouttype) पर रखी जाएँगी।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट मान है  **HandoutType.Handouts6Horizontal** .

**वापसी:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```

यह निर्दिष्ट करता है कि कितनी स्लाइड्स और किस क्रम में पृष्ठ [HandoutType](../../com.aspose.slides/handouttype) पर रखी जाएँगी।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट मान है  **HandoutType.Handouts6Horizontal** .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```

यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबरों को प्रिंट किया जाए या नहीं।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट मान है  **true** .

**वापसी:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```

यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबरों को प्रिंट किया जाए या नहीं।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट मान है  **true** .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```

यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड्स के चारों ओर फ्रेम खींचा जाए या नहीं।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट मान है  **true** .

**वापसी:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```

यह निर्दिष्ट करता है कि प्रदर्शित स्लाइड्स के चारों ओर फ्रेम खींचा जाए या नहीं।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट मान है  **true** .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```

यह निर्दिष्ट करता है कि स्लाइड्स पर टिप्पणी दिखाएँ या न दिखाएँ

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट मान है  **false** .

**वापसी:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```

यह निर्दिष्ट करता है कि स्लाइड्स पर टिप्पणी दिखाएँ या न दिखाएँ

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट मान है  **false** .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |