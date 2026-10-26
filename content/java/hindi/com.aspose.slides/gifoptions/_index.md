---
title: GifOptions
second_title: Aspose.Slides के लिए Java API संदर्भ
description: GIF निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/gifoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी कार्यान्वित इंटरफ़ेस:**  
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
>      gifOptions.setFrameSize(new Dimension(960, 720)); // परिणामी GIF का आकार
>      gifOptions.setDefaultDelay(2000); // प्रत्येक स्लाइड कितनी देर तक दिखेगी जब तक कि अगली स्लाइड पर नहीं बदला जाता
>      gifOptions.setTransitionFps(35); // बेहतर ट्रांज़िशन एनीमेशन गुणवत्ता के लिए FPS बढ़ाएँ
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions क्लास का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | फ़्रेम आकार को प्राप्त करता है या सेट करता है। |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | फ़्रेम आकार को प्राप्त करता है या सेट करता है। |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। |
| [getTransitionFps()](#getTransitionFps--) | ट्रांज़िशन FPS [फ़्रेम/सेकंड] को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है। |
| [setTransitionFps(int value)](#setTransitionFps-int-) | ट्रांज़िशन FPS [फ़्रेम/सेकंड] को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है। |
| [getDefaultDelay()](#getDefaultDelay--) | डिफ़ॉल्ट देरी समय [ms] को प्राप्त करता है या सेट करता है। |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | डिफ़ॉल्ट देरी समय [ms] को प्राप्त करता है या सेट करता है। |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions क्लास का एक नया उदाहरण प्रारंभ करता है।

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```


फ़्रेम आकार को प्राप्त करता है या सेट करता है।

--------------------

यदि आकार खाली है तो मान [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) से लिया जाएगा।

**वापसी:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```


फ़्रेम आकार को प्राप्त करता है या सेट करता है।

--------------------

यदि आकार खाली है तो मान [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) से लिया जाएगा।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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
public final void setExportHiddenSlides(boolean value)
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
public final int getTransitionFps()
```


ट्रांज़िशन FPS [फ़्रेम/सेकंड] को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है।

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
public final void setTransitionFps(int value)
```


ट्रांज़िशन FPS [फ़्रेम/सेकंड] को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 25 है।

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


डिफ़ॉल्ट देरी समय [ms] को प्राप्त करता है या सेट करता है। यह मान उपयोग किया जाएगा यदि [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) सेट नहीं है। डिफ़ॉल्ट मान 1000 है।

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
public final void setDefaultDelay(int value)
```


डिफ़ॉल्ट देरी समय [ms] को प्राप्त करता है या सेट करता है। यह मान उपयोग किया जाएगा यदि [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) सेट नहीं है। डिफ़ॉल्ट मान 1000 है।

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