---
title: SaveOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक सार वर्ग जिसमें विकल्प होते हैं जो निर्धारित करते हैं कि प्रस्तुति कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/saveoptions/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

वैकल्पिक वर्ग जिसमें विकल्प होते हैं जो प्रस्तुतिकरण को सहेजने के तरीके को नियंत्रित करते हैं।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | वॉर्निंग प्राप्त करने वाले और यह निर्णय लेने वाले ऑब्जेक्ट को लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द कर दी जाएगी। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | वॉर्निंग प्राप्त करने वाले और यह निर्णय लेने वाले ऑब्जेक्ट को लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द कर दी जाएगी। |
| [getProgressCallback()](#getProgressCallback--) | सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। |
| [getGradientStyle()](#getGradientStyle--) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। |
| [setGradientStyle(int value)](#setGradientStyle-int-) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्दिष्ट करता है। |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्दिष्ट करता है। |

### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

वॉर्निंग प्राप्त करने वाले और यह निर्णय लेने वाले ऑब्जेक्ट को लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द कर दी जाएगी। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**वापसी:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

वॉर्निंग प्राप्त करने वाले और यह निर्णय लेने वाले ऑब्जेक्ट को लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द कर दी जाएगी। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**वापसी:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

सहेजने की प्रगति अपडेट को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें-लिखें String.

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
public final void setDefaultRegularFont(String value)
```

स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें-लिखें String.

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
public final int getGradientStyle()
```

ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [GradientStyle](../../com.aspose.slides/gradientstyle).

**वापसी:**
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [GradientStyle](../../com.aspose.slides/gradientstyle).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्दिष्ट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

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

जब इस प्रॉपर्टी को true पर सेट किया जाता है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को सहेजते समय अनदेखा किया जाएगा।

जब इस प्रॉपर्टी को false पर सेट किया जाता है, तो सभी हाइपरलिंक्स सहेजे जाएंगे।

**वापसी:**
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्दिष्ट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

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

जब इस प्रॉपर्टी को true पर सेट किया जाता है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को सहेजते समय अनदेखा किया जाएगा।

जब इस प्रॉपर्टी को false पर सेट किया जाता है, तो सभी हाइपरलिंक्स सहेजे जाएंगे।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |