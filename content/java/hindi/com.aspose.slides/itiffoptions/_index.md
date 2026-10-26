---
title: ITiffOptions
second_title: Aspose.Slides for Java API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति TIFF फ़ॉर्मेट में कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/itiffoptions/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति TIFF प्रारूप में कैसे सहेजी जाती है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImageSize()](#getImageSize--) | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। |
| [getDpiX()](#getDpiX--) | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [setDpiX(long value)](#setDpiX-long-) | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [getDpiY()](#getDpiY--) | डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [setDpiY(long value)](#setDpiY-long-) | डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं, यह निर्दिष्ट करता है। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं, यह निर्दिष्ट करता है। |
| [getCompressionType()](#getCompressionType--) | संपीड़न प्रकार निर्दिष्ट करता है। |
| [setCompressionType(int value)](#setCompressionType-int-) | संपीड़न प्रकार निर्दिष्ट करता है। |
| [getPixelFormat()](#getPixelFormat--) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। |
| [setPixelFormat(int value)](#setPixelFormat-int-) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getBwConversionMode()](#getBwConversionMode--) | रंगीन छवि को काली-सफ़ेद छवि में बदलने के लिए एल्गोरिथ्म निर्दिष्ट करता है। |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | रंगीन छवि को काली-सफ़ेद छवि में बदलने के लिए एल्गोरिथ्म निर्दिष्ट करता है। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति नियंत्रित करने के विकल्प प्रदान करता है। |

### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार के आधार पर गणना किए जाएंगे। पढ़ें/लिखें java.awt.Dimension।

**वापसी:**
java.awt.Dimension

### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार के आधार पर गणना किए जाएंगे। पढ़ें/लिखें java.awt.Dimension।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long।

**वापसी:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long।

**वापसी:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट false है।

**वापसी:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

संपीड़न प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**वापसी:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

संपीड़न प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

**वापसी:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> उदाहरण:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

रंगीन छवि को काली-सफ़ेद छवि में बदलने के लिए एल्गोरिथ्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट हो। पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)।

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

रंगीन छवि को काली-सफ़ेद छवि में बदलने के लिए एल्गोरिथ्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट हो। पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)।

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति नियंत्रित करने के विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)