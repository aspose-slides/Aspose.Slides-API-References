---
title: SaveOptions
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक एब्स्ट्रैक्ट क्लास जिसमें विकल्प होते हैं जो यह नियंत्रित करते हैं कि प्रस्तुति कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/saveoptions/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

विकल्पों के साथ एक अब्स्ट्रैक्ट क्लास जो प्रस्तुतिकरण को सहेजने के तरीके को नियंत्रित करती है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [getProgressCallback()](#getProgressCallback--) | Represents a callback object for saving progress updates in percentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Represents a callback object for saving progress updates in percentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returns or sets font used in case source font is not found. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returns or sets font used in case source font is not found. |
| [getGradientStyle()](#getGradientStyle--) | Returns or sets the visual style of the gradient. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Returns or sets the visual style of the gradient. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. |

### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

एक ऑब्जेक्ट लौटाता/सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback)।

**रिटर्न:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

एक ऑब्जेक्ट लौटाता/सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

सेविंग प्रोग्रेस अपडेट्स प्रतिशत में दर्शाने के लिये एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback)।

**रिटर्न:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

सेविंग प्रोग्रेस अपडेट्स प्रतिशत में दर्शाने के लिये एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [IProgressCallback](../../com.aspose.slides/iprogresscallback)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

फ़ॉन्ट लौटाता या सेट करता है जो स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाता है। पढ़ें-लिखें String.

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
public final void setDefaultRegularFont(String value)
```

फ़ॉन्ट लौटाता या सेट करता है जो स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाता है। पढ़ें-लिखें String.

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

विज़ुअल स्टाइल ऑफ द ग्रेडिएंट को लौटाता या सेट करता है। पढ़ें/लिखें [GradientStyle](../../com.aspose.slides/gradientstyle)।

**रिटर्न:**
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

विज़ुअल स्टाइल ऑफ द ग्रेडिएंट को लौटाता या सेट करता है। पढ़ें/लिखें [GradientStyle](../../com.aspose.slides/gradientstyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

निर्दिष्ट करता है कि प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

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

जब यह प्रॉपर्टी true पर सेट की जाती है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक सहेजते समय अनदेखे किए जाएंगे।

जब यह प्रॉपर्टी false पर सेट की जाती है, तो सभी हाइपरलिंक सहेजे जाएंगे।

**रिटर्न:**
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

निर्दिष्ट करता है कि प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

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

जब यह प्रॉपर्टी true पर सेट की जाती है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक सहेजते समय अनदेखे किए जाएंगे।

जब यह प्रॉपर्टी false पर सेट की जाती है, तो सभी हाइपरलिंक सहेजे जाएंगे।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |