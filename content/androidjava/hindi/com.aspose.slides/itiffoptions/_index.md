---
title: ITiffOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: विकल्प प्रदान करता है जो निर्धारित करता है कि प्रस्तुति को TIFF प्रारूप में कैसे सहेजा जाता है।
type: docs
url: /hi/com.aspose.slides/itiffoptions/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

विकल्प प्रदान करता है जो निर्धारित करता है कि प्रस्तुति को TIFF प्रारूप में कैसे सहेजा जाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImageSize()](#getImageSize--) | एक उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | एक उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। |
| [getDpiX()](#getDpiX--) | डॉट प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [setDpiX(long value)](#setDpiX-long-) | डॉट प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [getDpiY()](#getDpiY--) | डॉट प्रति इंच में लंबवत रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [setDpiY(long value)](#setDpiY-long-) | डॉट प्रति इंच में लंबवत रिज़ॉल्यूशन निर्दिष्ट करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल करनी हैं या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल करनी हैं या नहीं। |
| [getCompressionType()](#getCompressionType--) | कम्प्रेशन प्रकार निर्धारित करता है। |
| [setCompressionType(int value)](#setCompressionType-int-) | कम्प्रेशन प्रकार निर्धारित करता है। |
| [getPixelFormat()](#getPixelFormat--) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। |
| [setPixelFormat(int value)](#setPixelFormat-int-) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getBwConversionMode()](#getBwConversionMode--) | रंगीन छवि को काले और सफेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है। |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | रंगीन छवि को काले और सफेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है। |
| [getInkOptions()](#getInkOptions--) | निर्यातित दस्तावेज़ में इंक ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

एक उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किए जाएंगे। पढ़ें/लिखें [Size](../../com.aspose.slides.android/size)।

**रिटर्न:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

एक उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किए जाएंगे। पढ़ें/लिखें [Size](../../com.aspose.slides.android/size)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

डॉट प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long.

**रिटर्न:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

डॉट प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

डॉट प्रति इंच में लंबवत रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long.

**रिटर्न:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

डॉट प्रति इंच में लंबवत रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें long.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल करनी हैं या नहीं। डिफ़ॉल्ट false है।

**रिटर्न:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल करनी हैं या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

कम्प्रेशन प्रकार निर्धारित करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**रिटर्न:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

कम्प्रेशन प्रकार निर्धारित करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

**रिटर्न:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

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

**रिटर्न:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

रंगीन छवि को काली और सफेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) को [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट किया गया हो पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default) है।

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

**रिटर्न:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

रंगीन छवि को काली और सफेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) को [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट किया गया हो पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default) है।

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

निर्यातित दस्तावेज़ में इंक ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न:**
[IInkOptions](../../com.aspose.slides/iinkoptions)