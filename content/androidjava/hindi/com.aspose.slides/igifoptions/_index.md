---
title: IGifOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: GIF निर्यात विकल्पों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/igifoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

GIF निर्यात विकल्पों को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | फ़्रेम आकार प्राप्त करता है या सेट करता है। |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | फ़्रेम आकार प्राप्त करता है या सेट करता है। |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। |
| [getTransitionFps()](#getTransitionFps--) | संक्रमण FPS [फ़्रेम/सेक] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है। |
| [setTransitionFps(int value)](#setTransitionFps-int-) | संक्रमण FPS [फ़्रेम/सेक] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है। |
| [getDefaultDelay()](#getDefaultDelay--) | डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है या सेट करता है। |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है या सेट करता है। |

### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

फ़्रेम आकार प्राप्त करता है या सेट करता है।

--------------------

यदि आकार खाली है तो मान [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) से लिया जाएगा।

**वापसी:**  
[Size](../../com.aspose.slides.android/size)

### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

फ़्रेम आकार प्राप्त करता है या सेट करता है।

--------------------

यदि आकार खाली है तो मान [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) से लिया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**  
boolean

### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

संक्रमण FPS [फ़्रेम/सेक] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**  
int

### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

संक्रमण FPS [फ़्रेम/सेक] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है या सेट करता है। यह मान [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) सेट न होने पर उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**  
int

### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है या सेट करता है। यह मान [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) सेट न होने पर उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |