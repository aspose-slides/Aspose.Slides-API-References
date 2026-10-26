---
title: GifOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: GIF निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/gifoptions/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

GIF निर्यात विकल्पों का प्रतिनिधित्व करता है।

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // परिणामस्वरूप GIF का आकार
>      gifOptions.setDefaultDelay(2000); // प्रत्येक स्लाइड कितनी देर तक दिखाई जाएगी जब वह अगले पर बदल जाएगी
>      gifOptions.setTransitionFps(35); // बेहतर ट्रांज़िशन एनीमेशन गुणवत्ता के लिए FPS बढ़ाएँ
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## कन्स्ट्रक्टर

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | फ़्रेम आकार प्राप्त करता है या सेट करता है। |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | फ़्रेम आकार प्राप्त करता है या सेट करता है। |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात होंगी या नहीं। |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात होंगी या नहीं। |
| [getTransitionFps()](#getTransitionFps--) | परिवर्तन FPS [frames/sec] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है। |
| [setTransitionFps(int value)](#setTransitionFps-int-) | परिवर्तन FPS [frames/sec] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है। |
| [getDefaultDelay()](#getDefaultDelay--) | डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है या सेट करता है। |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है या सेट करता है। |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


फ़्रेम आकार प्राप्त करता है या सेट करता है।

--------------------

यदि आकार खाली है तो मान [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) से लिया जाएगा।

**रिटर्न:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
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
public final boolean getExportHiddenSlides()
```


निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात होंगी या नहीं। डिफ़ॉल्ट मान false है।

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

**रिटर्न:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात होंगी या नहीं। डिफ़ॉल्ट मान false है।

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
public final int getTransitionFps()
```


परिवर्तन FPS [frames/sec] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है।

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

**रिटर्न:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


परिवर्तन FPS [frames/sec] प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है।

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
public final int getDefaultDelay()
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

**रिटर्न:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
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