---
title: Html5Options
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/html5options/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**
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
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [Html5Options()](#Html5Options--) | डिफ़ॉल्ट निर्माणकर्ता। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | ट्रांज़िशन एनीमेशन विकल्प को लौटाता या सेट करता है। |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | ट्रांज़िशन एनीमेशन विकल्प को लौटाता या सेट करता है। |
| [getAnimateShapes()](#getAnimateShapes--) | आकार एनीमेशन विकल्प को लौटाता या सेट करता है। |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | आकार एनीमेशन विकल्प को लौटाता या सेट करता है। |
| [getEmbedImages()](#getEmbedImages--) | छवि एम्बेडिंग विकल्प को लौटाता या सेट करता है। |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | छवि एम्बेडिंग विकल्प को लौटाता या सेट करता है। |
| [getOutputPath()](#getOutputPath--) | बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए, यह निर्धारित करता है। |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए, यह निर्धारित करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह निर्धारित करने के लिए मान प्राप्त या सेट करता है कि टेक्स्ट को लिगैचर के बिना रेंडर किया जाए। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह निर्धारित करने के लिए मान प्राप्त या सेट करता है कि टेक्स्ट को लिगैचर के बिना रेंडर किया जाए। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


डिफ़ॉल्ट निर्माणकर्ता।

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```


ट्रांज़िशन एनीमेशन विकल्प को लौटाता या सेट करता है। पढ़ें/लिखें बूलियन।

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


ट्रांज़िशन एनीमेशन विकल्प को लौटाता या सेट करता है। पढ़ें/लिखें बूलियन।

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


आकार एनीमेशन विकल्प को लौटाता या सेट करता है। पढ़ें/लिखें बूलियन।

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


आकार एनीमेशन विकल्प को लौटाता या सेट करता है। पढ़ें/लिखें बूलियन।

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


छवि एम्बेडिंग विकल्प को लौटाता या सेट करता है। पढ़ें/लिखें बूलियन।

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
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```


छवि एम्बेडिंग विकल्प को लौटाता या सेट करता है। पढ़ें/लिखें बूलियन।

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


बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए, यह निर्धारित करता है। पढ़ें/लिखें स्ट्रिंग।

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


बाहरी संसाधनों को कहाँ संग्रहीत किया जाना चाहिए, यह निर्धारित करता है। पढ़ें/लिखें स्ट्रिंग।

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

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


यह निर्धारित करने के लिए मान प्राप्त या सेट करता है कि टेक्स्ट को लिगैचर के बिना रेंडर किया जाए। जब true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगैचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से यह गुण false पर सेट होता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगैचर को निष्क्रिय करें
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


यह निर्धारित करने के लिए मान प्राप्त या सेट करता है कि टेक्स्ट को लिगैचर के बिना रेंडर किया जाए। जब true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगैचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से यह गुण false पर सेट होता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगैचर को निष्क्रिय करें
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


प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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


प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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