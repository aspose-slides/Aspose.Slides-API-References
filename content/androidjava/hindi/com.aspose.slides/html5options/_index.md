---
title: Html5Options
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/html5options/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी कार्यान्वित इंटरफेस:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
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
## निर्माता

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Html5Options()](#Html5Options--) | डिफ़ॉल्ट कंस्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | ट्रांज़िशन एनीमेशन विकल्प को वापस देता है या सेट करता है। |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | ट्रांज़िशन एनीमेशन विकल्प को वापस देता है या सेट करता है। |
| [getAnimateShapes()](#getAnimateShapes--) | शेप्स एनीमेशन विकल्प को वापस देता है या सेट करता है। |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | शेप्स एनीमेशन विकल्प को वापस देता है या सेट करता है। |
| [getEmbedImages()](#getEmbedImages--) | इमेजेज एम्बेडिंग विकल्प को वापस देता है या सेट करता है। |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | इमेजेज एम्बेडिंग विकल्प को वापस देता है या सेट करता है। |
| [getOutputPath()](#getOutputPath--) | यह निर्धारित करता है कि बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए। |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | यह निर्धारित करता है कि बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह निर्धारित करने वाला मान प्राप्त या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया जाए या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह निर्धारित करने वाला मान प्राप्त या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया जाए या नहीं। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है। |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


डिफ़ॉल्ट कंस्ट्रक्टर।

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```


ट्रांज़िशन एनीमेशन विकल्प को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```


ट्रांज़िशन एनीमेशन विकल्प को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```


शेप्स एनीमेशन विकल्प को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```


शेप्स एनीमेशन विकल्प को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```


इमेजेज एम्बेडिंग विकल्प को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

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
public final void setEmbedImages(boolean value)
```


इमेजेज एम्बेडिंग विकल्प को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```


यह निर्धारित करता है कि बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए। पढ़ने/लिखने योग्य स्ट्रिंग।

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
public final void setOutputPath(String value)
```


यह निर्धारित करता है कि बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए। पढ़ने/लिखने योग्य स्ट्रिंग।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


चित्र संपीड़न स्तर का प्रतिनिधित्व करता है

**रिटर्न:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


चित्र संपीड़न स्तर का प्रतिनिधित्व करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


यह निर्धारित करने वाला मान प्राप्त या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया जाए या नहीं। जब true पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट रहती है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को निष्क्रिय करें
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
public final void setDisableFontLigatures(boolean value)
```


यह निर्धारित करने वाला मान प्राप्त या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया जाए या नहीं। जब true पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट रहती है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को निष्क्रिय करें
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है।

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |