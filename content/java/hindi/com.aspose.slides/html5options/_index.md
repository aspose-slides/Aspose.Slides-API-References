---
title: Html5Options
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/html5options/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

HTML5 एक्सपोर्ट विकल्पों को दर्शाता है।

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
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Html5Options()](#Html5Options--) | डिफ़ॉल्ट कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | ट्रांज़िशन एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | ट्रांज़िशन एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। |
| [getAnimateShapes()](#getAnimateShapes--) | शेप्स एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | शेप्स एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। |
| [getEmbedImages()](#getEmbedImages--) | इमेज एम्बेडिंग विकल्प को प्राप्त करता है या सेट करता है। |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | इमेज एम्बेडिंग विकल्प को प्राप्त करता है या सेट करता है। |
| [getOutputPath()](#getOutputPath--) | यह निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाएँ। |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | यह निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाएँ। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्रों के संकुचन स्तर को दर्शाता है |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्रों के संकुचन स्तर को दर्शाता है |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, इस मान को प्राप्त करता है या सेट करता है। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, इस मान को प्राप्त करता है या सेट करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रेजेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) को एक्सपोर्ट करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रेजेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) को एक्सपोर्ट करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है। |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


डिफ़ॉल्ट कंस्ट्रक्टर।

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```


ट्रांज़िशन एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

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

**वापसी:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```


ट्रांज़िशन एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

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


शेप्स एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

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

**वापसी:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```


शेप्स एनिमेशन विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

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


इमेज एम्बेडिंग विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

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

**वापसी:**
boolean
### setEmbedImages(String value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```


इमेज एम्बेडिंग विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

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


यह निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाएँ। पढ़ने/लिखने योग्य String।

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

**वापसी:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```


यह निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाएँ। पढ़ने/लिखने योग्य String।

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


चित्रों के संकुचन स्तर को दर्शाता है

**वापसी:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


चित्रों के संकुचन स्तर को दर्शाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, इस मान को प्राप्त करता है या सेट करता है। जब true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएँगे। डिफ़ॉल्ट रूप से, इस गुण का मान false रहता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर अक्षम करें
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


लिगेचर का उपयोग किए बिना टेक्स्ट रेंडर किया जाता है या नहीं, इस मान को प्राप्त करता है या सेट करता है। जब true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएँगे। डिफ़ॉल्ट रूप से, इस गुण का मान false रहता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर अक्षम करें
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


प्रेजेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) को एक्सपोर्ट करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है।

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

**वापसी:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


प्रेजेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) को एक्सपोर्ट करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है।

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