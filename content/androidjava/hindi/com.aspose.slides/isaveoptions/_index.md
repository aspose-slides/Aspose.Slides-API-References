---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /hi/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

विकल्प जो नियंत्रित करते हैं कि प्रस्तुति कैसे सहेजी जाती है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | चेतावनियाँ प्राप्त करने वाला और यह निर्धारित करने वाला कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी, ऐसा ऑब्जेक्ट लौटाता है या सेट करता है। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | चेतावनियाँ प्राप्त करने वाला और यह निर्धारित करने वाला कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी, ऐसा ऑब्जेक्ट लौटाता है या सेट करता है। |
| [getProgressCallback()](#getProgressCallback--) | सेविंग प्रक्रिया की प्रगति को प्रतिशत में अपडेट करने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | सेविंग प्रक्रिया की प्रगति को प्रतिशत में अपडेट करने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। |
| [getGradientStyle()](#getGradientStyle--) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। |
| [setGradientStyle(int value)](#setGradientStyle-int-) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

चेतावनियाँ प्राप्त करने वाला और यह निर्धारित करने वाला कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी, ऐसा ऑब्जेक्ट लौटाता है या सेट करता है। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**रिटर्न:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

चेतावनियाँ प्राप्त करने वाला और यह निर्धारित करने वाला कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी, ऐसा ऑब्जेक्ट लौटाता है या सेट करता है। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

सेविंग प्रक्रिया की प्रगति को प्रतिशत में अपडेट करने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**रिटर्न:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

सेविंग प्रक्रिया की प्रगति को प्रतिशत में अपडेट करने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें-लिखें String.

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


**रिटर्न:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें-लिखें String.

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

ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [GradientStyle](../../com.aspose.slides/gradientstyle).

**रिटर्न:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [GradientStyle](../../com.aspose.slides/gradientstyle).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

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


जब यह प्रॉपर्टी true पर सेट की जाती है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक को सहेजने के दौरान अनदेखा कर दिया जाएगा।

जब यह प्रॉपर्टी false पर सेट की जाती है, तो सभी हाइपरलिंक सहेजे जाएंगे।

**रिटर्न:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

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

जब यह प्रॉपर्टी true पर सेट की जाती है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक को सहेजने के दौरान अनदेखा कर दिया जाएगा।

जब यह प्रॉपर्टी false पर सेट की जाती है, तो सभी हाइपरलिंक सहेजे जाएंगे।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |