---
title: IHtml5Options
second_title: Aspose.Slides for Android के लिए जावा API रेफ़रेंस
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ihtml5options/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

HTML5 एक्सपोर्टिंग विकल्पों का प्रतिनिधित्व करता है।

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
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | ट्रांज़िशन एनिमेशन विकल्प को लौटाता है या सेट करता है। |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | ट्रांज़िशन एनिमेशन विकल्प को लौटाता है या सेट करता है। |
| [getAnimateShapes()](#getAnimateShapes--) | शेप्स एनिमेशन विकल्प को लौटाता है या सेट करता है। |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | शेप्स एनिमेशन विकल्प को लौटाता है या सेट करता है। |
| [getEmbedImages()](#getEmbedImages--) | इमेज एम्बेडिंग विकल्प को लौटाता है या सेट करता है। |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | इमेज एम्बेडिंग विकल्प को लौटाता है या सेट करता है। |
| [getOutputPath()](#getOutputPath--) | निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रेजेंटेशन एक्सपोर्ट करते समय स्लाइड्स पेज पर स्थित होने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रेजेंटेशन एक्सपोर्ट करते समय स्लाइड्स पेज पर स्थित होने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

ट्रांज़िशन एनिमेशन विकल्प को लौटाता है या सेट करता है। पढ़ें/लिखें boolean.

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

ट्रांज़िशन एनिमेशन विकल्प को लौटाता है या सेट करता है। पढ़ें/लिखें boolean.

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```

शेप्स एनिमेशन विकल्प को लौटाता है या सेट करता है। पढ़ें/लिखें boolean.

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

शेप्स एनिमेशन विकल्प को लौटाता है या सेट करता है। पढ़ें/लिखें boolean.

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```

इमेज एम्बेडिंग विकल्प को लौटाता है या सेट करता है। पढ़ें/लिखें boolean.

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

इमेज एम्बेडिंग विकल्प को लौटाता है या सेट करता है। पढ़ें/लिखें boolean.

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
public abstract String getOutputPath()
```

निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। पढ़ें/लिखें String.

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

निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। पढ़ें/लिखें String.

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
public abstract boolean getDisableFontLigatures()
```

एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट रहती है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर को अक्षम करें
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

एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट रहती है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर को अक्षम करें
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
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

एक मोड प्राप्त करता या सेट करता है जिसमें स्लाइड्स पेज पर रखी जाती हैं जब प्रेजेंटेशन एक्सपोर्ट किया जाता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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

एक मोड प्राप्त करता या सेट करता है जिसमें स्लाइड्स पेज पर रखी जाती हैं जब प्रेजेंटेशन एक्सपोर्ट किया जाता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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