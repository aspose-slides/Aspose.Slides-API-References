---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: प्रस्तुति को सहेजने के तरीके को नियंत्रित करने वाले विकल्प.
type: docs
url: /hi/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

प्रस्तुति को सहेजने के तरीके को नियंत्रित करने वाले विकल्प।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | चेतावनियों को प्राप्त करने और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | चेतावनियों को प्राप्त करने और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। |
| [getProgressCallback()](#getProgressCallback--) | सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getGradientStyle()](#getGradientStyle--) | ग्रेडियंट की दृश्य शैली को प्राप्त करता है या सेट करता है। |
| [setGradientStyle(int value)](#setGradientStyle-int-) | ग्रेडियंट की दृश्य शैली को प्राप्त करता है या सेट करता है। |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

चेतावनियों को प्राप्त करने और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। पढ़ने/लिखने [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**वापसी:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

चेतावनियों को प्राप्त करने और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। पढ़ने/लिखने [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**वापसी:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ने-लिखने String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ने-लिखने String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

ग्रेडियंट की दृश्य शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने [GradientStyle](../../com.aspose.slides/gradientstyle).

**वापसी:**
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

ग्रेडियंट की दृश्य शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने [GradientStyle](../../com.aspose.slides/gradientstyle).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। पढ़ने/लिखने boolean. डिफ़ॉल्ट मान false है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

जब यह प्रॉपर्टी true पर सेट की जाती है, जावास्क्रिप्ट कॉल वाले हाइपरलिंक सहेजते समय अनदेखे कर दिए जाएंगे।

जब यह प्रॉपर्टी false पर सेट की जाती है, सभी हाइपरलिंक सहेजे जाएंगे।

**वापसी:**
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। पढ़ने/लिखने boolean. डिफ़ॉल्ट मान false है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

जब यह प्रॉपर्टी true पर सेट की جاتی है, जावास्क्रिप्ट कॉल वाले हाइपरलिंक सहेजते समय अनदेखे कर दिए जाएंगे।

जब यह प्रॉपर्टी false पर सेट की جاتی है, सभी हाइपरलिंक सहेजे जाएंगे।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |