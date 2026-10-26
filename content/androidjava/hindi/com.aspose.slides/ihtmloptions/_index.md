---
title: IHtmlOptions
second_title: Aspose.Slides Android के लिए, Java API रेफ़रेंस के माध्यम से
description: HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ihtmloptions/
---
**सभी लागू किए गए इंटरफ़ेस:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

HTML निर्यात विकल्प का प्रतिनिधित्व करता है।

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML टेम्पलेट को लौटाता या सेट करता है। |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML टेम्पलेट को लौटाता या सेट करता है। |
| [getSlideImageFormat()](#getSlideImageFormat--) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को लौटाता या सेट करता है। |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को लौटाता या सेट करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | एक बूलियन फ़्लैग यह दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | एक बूलियन फ़्लैग यह दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए True - इससे लेआउट रिस्पॉन्सिव हो जाएगा। |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए True - इससे लेआउट रिस्पॉन्सिव हो जाएगा। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रेज़ेंटेशन निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रेज़ेंटेशन निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getInkOptions()](#getInkOptions--) | निर्यात दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

HTML टेम्पलेट को लौटाता या सेट करता है। पढ़ें/लिखें [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)।

**वापसी:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

HTML टेम्पलेट को लौटाता या सेट करता है। पढ़ें/लिखें [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

स्लाइड इमेज फ़ॉर्मेट विकल्पों को लौटाता या सेट करता है। पढ़ें/लिखें [ISlideImageFormat](../../com.aspose.slides/islideimageformat)।

**वापसी:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

स्लाइड इमेज फ़ॉर्मेट विकल्पों को लौटाता या सेट करता है। पढ़ें/लिखें [ISlideImageFormat](../../com.aspose.slides/islideimageformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट false है।

**वापसी:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। पढ़ें/लिखें byte.

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियाँ हों।

PDF फ़ॉर्मेट में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता को प्राप्त या सेट करने के लिए इस प्रॉपर्टी का उपयोग करें। मान 0 से 100 तक हो सकता है जहाँ 0 सबसे ख़राब गुणवत्ता पर अधिकतम संपीड़न और 100 सर्वोत्तम गुणवत्ता पर न्यूनतम संपीड़न दर्शाता है।

डिफ़ॉल्ट मान **95** है।

**वापसी:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। पढ़ें/लिखें byte.

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियाँ हों।

PDF फ़ॉर्मेट में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता को प्राप्त या सेट करने के लिए इस प्रॉपर्टी का उपयोग करें। मान 0 से 100 तक हो सकता है जहाँ 0 सबसे ख़राब गुणवत्ता पर अधिकतम संपीड़न और 100 सर्वोत्तम गुणवत्ता पर न्यूनतम संपीड़न दर्शाता है।

डिफ़ॉल्ट मान **95** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))।

**वापसी:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

एक बूलियन फ़्लैग यह दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में सीरियलाइज़ हो जाएंगे (जिससे फ़ाइल बड़ा हो सकती है) पढ़ें/लिखें boolean।

**वापसी:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

एक बूलियन फ़्लैग यह दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में सीरियलाइज़ हो जाएंगे (जिससे फ़ाइल बड़ा हो सकती है) पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए True - इससे लेआउट रिस्पॉन्सिव हो जाएगा। False - अन्यथा। पढ़ें/लिखें boolean।

**वापसी:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को हटाने के लिए True - इससे लेआउट रिस्पॉन्सिव हो जाएगा। False - अन्यथा। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

टेक्स्ट को लिगेचर के बिना रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से यह प्रॉपर्टी false है।

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
public abstract void setDisableFontLigatures(boolean value)
```

टेक्स्ट को लिगेचर के बिना रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से यह प्रॉपर्टी false है।

--------------------

> ```
> उदाहरण:
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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रेज़ेंटेशन निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> उदाहरण:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्रेज़ेंटेशन निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> उदाहरण:
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
public abstract IInkOptions getInkOptions()
```

निर्यात दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)