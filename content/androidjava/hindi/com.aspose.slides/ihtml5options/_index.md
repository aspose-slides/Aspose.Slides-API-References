---
title: IHtml5Options
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API संदर्भ के माध्यम से
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ihtml5options/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | ट्रांज़िशन एनीमेशन विकल्प को लौटाता है या सेट करता है। |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | ट्रांज़िशन एनीमेशन विकल्प को लौटाता है या सेट करता है। |
| [getAnimateShapes()](#getAnimateShapes--) | शेप्स एनीमेशन विकल्प को लौटाता है या सेट करता है। |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | शेप्स एनीमेशन विकल्प को लौटाता है या सेट करता है। |
| [getEmbedImages()](#getEmbedImages--) | छवियों एम्बेडिंग विकल्प को लौटाता है या सेट करता है। |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | छवियों एम्बेडिंग विकल्प को लौटाता है या सेट करता है। |
| [getOutputPath()](#getOutputPath--) | निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है Read/write  PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है Read/write  PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, दर्शाने वाला मान प्राप्त या सेट करता है। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, दर्शाने वाला मान प्राप्त या सेट करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```


ट्रांज़िशन एनीमेशन विकल्प को लौटाता है या सेट करता है। Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```


ट्रांज़िशन एनीमेशन विकल्प को लौटाता है या सेट करता है। Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```


शेप्स एनीमेशन विकल्प को लौटाता है या सेट करता है। Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```


शेप्स एनीमेशन विकल्प को लौटाता है या सेट करता है। Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```


छवियों एम्बेडिंग विकल्प को लौटाता है या सेट करता है। Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public abstract void setEmbedImages(boolean value)
```


छवियां एम्बेडिंग विकल्प को लौटाता है या सेट करता है। Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public abstract String getOutputPath()
```


निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। Read/write String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public abstract void setOutputPath(String value)
```


निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। Read/write String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है Read/write  PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**रिटर्न:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है Read/write  PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, दर्शाने वाला मान प्राप्त या सेट करता है। जब true पर सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर निष्क्रिय करें
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, दर्शाने वाला मान प्राप्त या सेट करता है। जब true पर सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर निष्क्रिय करें
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |