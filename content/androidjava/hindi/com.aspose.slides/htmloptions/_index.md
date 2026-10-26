---
title: HtmlOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/htmloptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)  
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Callback निर्दिष्ट करते हुए एक नया HtmlOptions ऑब्जेक्ट बनाता है। |
| [HtmlOptions()](#HtmlOptions--) | एकल HTML फ़ाइल में सहेजने के लिए नया HtmlOptions ऑब्जेक्ट बनाता है। |

## विधियां

| विधि | विवरण |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML टेम्पलेट को प्राप्त करता है या सेट करता है। |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML टेम्पलेट को प्राप्त करता है या सेट करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं। |
| [getSlideImageFormat()](#getSlideImageFormat--) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ में JPEG इमेज की गुणवत्ता निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ में JPEG इमेज की गुणवत्ता निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | यह बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ के भाग के रूप में रहेंगे या नहीं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | यह बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ के भाग के रूप में रहेंगे या नहीं। |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए true – इससे लेआउट उत्तरदायी बन जाता है। |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए true – इससे लेआउट उत्तरदायी बन जाता है। |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Callback निर्दिष्ट करते हुए एक नया HtmlOptions ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Callback ऑब्जेक्ट जो प्रोजेक्ट सहेजने को नियंत्रित करता है। |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

एकल HTML फ़ाइल में सहेजने के लिए नया HtmlOptions ऑब्जेक्ट बनाता है।

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न वैल्यू:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। **केवल-पठन** [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न वैल्यू:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**रिटर्न वैल्यू:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML टेम्पलेट को प्राप्त करता है या सेट करता है। **पठन/लेखन** [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)।

**रिटर्न वैल्यू:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML टेम्पलेट को प्राप्त करता है या सेट करता है। **पठन/लेखन** [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं। जब true सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से यह मान false है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न वैल्यू:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं। जब true सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से यह मान false है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। **पठन/लेखन** [ISlideImageFormat](../../com.aspose.slides/islideimageformat)।

**रिटर्न वैल्यू:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। **पठन/लेखन** [ISlideImageFormat](../../com.aspose.slides/islideimageformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF दस्तावेज़ में JPEG इमेज की गुणवत्ता निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। **पठन/लेखन** byte।

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG इमेज हों।

इस प्रॉपर्टी का उपयोग डॉक्यूमेंट को PDF फ़ॉर्मेट में सहेजते समय इमेज की गुणवत्ता को प्राप्त या सेट करने के लिए करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 न्यूनतम गुणवत्ता लेकिन अधिकतम संपीड़न दर्शाता है और 100 सर्वोत्तम गुणवत्ता लेकिन न्यूनतम संपीड़न।

डिफ़ॉल्ट मान **95** है।

**रिटर्न वैल्यू:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF दस्तावेज़ में JPEG इमेज की गुणवत्ता निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। **पठन/लेखन** byte।

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG इमेज हों।

इस प्रॉपर्टी का उपयोग डॉक्यूमेंट को PDF फ़ॉर्मेट में सहेजते समय इमेज की गुणवत्ता को प्राप्त या सेट करने के लिए करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 न्यूनतम गुणवत्ता लेकिन अधिकतम संपीड़न दर्शाता है और 100 सर्वोत्तम गुणवत्ता लेकिन न्यूनतम संपीड़न।

डिफ़ॉल्ट मान **95** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

चित्र संपीड़न स्तर का प्रतिनिधित्व करता है

**रिटर्न वैल्यू:**
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

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

यह बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ के भाग के रूप में रहेंगे या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिये जाएंगे, यदि false है तो वे दस्तावेज़ में अनुक्रमित रहेंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)।

**रिटर्न वैल्यू:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

यह बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ के भाग के रूप में रहेंगे या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिये जाएंगे, यदि false है तो वे दस्तावेज़ में अनुक्रमित रहेंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए true – इससे लेआउट उत्तरदायी बन जाता है। अन्यथा false। **पठन/लेखन** boolean।

**रिटर्न वैल्यू:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए true – इससे लेआउट उत्तरदायी बन जाता है। अन्यथा false। **पठन/लेखन** boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |