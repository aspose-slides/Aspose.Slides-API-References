---
title: HtmlOptions
second_title: Aspose.Slides for Java API संदर्भ
description: HTML निर्यात विकल्प का प्रतिनिधित्व करता है।
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

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | एक नया HtmlOptions ऑब्जेक्ट बनाता है जो कॉलबैक निर्दिष्ट करता है। |
| [HtmlOptions()](#HtmlOptions--) | एक नया HtmlOptions ऑब्जेक्ट बनाता है जो एकल HTML फ़ाइल में सहेजने के लिए उपयोग होता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getInkOptions()](#getInkOptions--) | एक्सपोर्टेड दस्तावेज़ में Ink ऑब्जेक्ट्स की रूपरेखा को नियंत्रित करने के विकल्प प्रदान करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्मित दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं, यह निर्दिष्ट करता है। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्मित दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं, यह निर्दिष्ट करता है। |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML टेम्प्लेट को प्राप्त करता है या सेट करता है। |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML टेम्प्लेट को प्राप्त करता है या सेट करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं, इसका मान प्राप्त करता है या सेट करता है। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं, इसका मान प्राप्त करता है या सेट करता है। |
| [getSlideImageFormat()](#getSlideImageFormat--) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ के भीतर JPEG इमेज की गुणवत्ता निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ के भीतर JPEG इमेज की गुणवत्ता निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है। |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है। |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर करने के लिए true - इससे लेआउट रिस्पॉन्सिव हो जाएगा। |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर करने के लिए true - इससे लेआउट रिस्पॉन्सिव हो जाएगा। |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

एक नया HtmlOptions ऑब्जेक्ट बनाता है जो कॉलबैक निर्दिष्ट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | सहेजने की प्रक्रिया को नियंत्रित करने वाला कॉलबैक ऑब्जेक्ट। |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

एक नया HtmlOptions ऑब्जेक्ट बनाता है जो एकल HTML फ़ाइल में सहेजने के लिए उपयोग होता है।

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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


**वापसी:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

एक्सपोर्टेड दस्तावेज़ में Ink ऑब्जेक्ट्स की रूपरेखा को नियंत्रित करने के विकल्प प्रदान करता है। केवल पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्मित दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट false है।

**वापसी:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्मित दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML टेम्प्लेट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)।

**वापसी:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML टेम्प्लेट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं, इसका मान प्राप्त करता है या सेट करता है। जब true सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

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


**वापसी:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं, इसका मान प्राप्त करता है या सेट करता है। जब true सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [ISlideImageFormat](../../com.aspose.slides/islideimageformat)।

**वापसी:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

स्लाइड इमेज फ़ॉर्मेट विकल्पों को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [ISlideImageFormat](../../com.aspose.slides/islideimageformat)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

JPEG इमेज की गुणवत्ता निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य बाइट।

--------------------

यह केवल तब प्रभावी है जब दस्तावेज़ में JPEG इमेजेज़ हों।

इस प्रॉपर्टी का उपयोग PDF फ़ॉर्मेट में सहेजते समय दस्तावेज़ के भीतर इमेज की गुणवत्ता प्राप्त करने या सेट करने के लिए किया जाता है। मान 0 से 100 के बीच हो सकता है जहाँ 0 का मतलब सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का मतलब सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **95** है।

**वापसी:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

JPEG इमेज की गुणवत्ता निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य बाइट।

--------------------

यह केवल तब प्रभावी है जब दस्तावेज़ में JPEG इमेजेज़ हों।

इस प्रॉपर्टी का उपयोग PDF फ़ॉर्मेट में सहेजते समय दस्तावेज़ के भीतर इमेज की गुणवत्ता प्राप्त करने या सेट करने के लिए किया जाता है। मान 0 से 100 के बीच हो सकता है जहाँ 0 का मतलब सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का मतलब सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **95** है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

चित्र संपीड़न स्तर का प्रतिनिधित्व करता है।

**वापसी:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

चित्र संपीड़न स्तर का प्रतिनिधित्व करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में सीरियलाइज़ हो जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)।

**वापसी:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में सीरियलाइज़ हो जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर करने के लिए true - इससे लेआउट रिस्पॉन्सिव हो जाएगा। अन्यथा false। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर करने के लिए true - इससे लेआउट रिस्पॉन्सिव हो जाएगा। अन्यथा false। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |