---
title: TiffOptions
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति को TIFF प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/tiffoptions/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

परिच्‍छेदन को TIFF रूप में सहेजने के विकल्प प्रदान करता है।

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // प्रस्तुति को TIFF दस्तावेज़ के रूप में सहेजना
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // TiffOptions क्लास का इंस्टांस बनाएं
>      TiffOptions opts = new TiffOptions();
>      // कम्प्रेशन प्रकार सेट कर रहे हैं
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // कम्प्रेशन प्रकार
>      // Default - डिफ़ॉल्ट कम्प्रेशन स्कीम (LZW) को निर्दिष्ट करता है।
>      // None - कोई कम्प्रेशन नहीं होने को निर्दिष्ट करता है।
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // गहराई कम्प्रेशन प्रकार पर निर्भर करती है और इसे मैन्युअली सेट नहीं किया जा सकता।
>      // रिज़ॉल्यूशन इकाई हमेशा 2 (डॉट्स प्रति इंच) के बराबर होती है।
>      // छवि DPI सेट कर रहे हैं
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // छवि आकार सेट करें
>      opts.setImageSize(new Dimension(1728, 1078));
>      // निर्दिष्ट छवि आकार के साथ प्रस्तुति को TIFF के रूप में सहेजें
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat में निम्न मान होते हैं (जैसा कि दस्तावेज़ीकरण से देखा जा सकता है):
>      //Format1bppIndexed; // 1 बिट प्रति पिक्सेल, इंडेक्स्ड।
>      //Format4bppIndexed; // 4 बिट प्रति पिक्सेल, इंडेक्स्ड।
>      //Format8bppIndexed; // 8 बिट प्रति पिक्सेल, इंडेक्स्ड।
>      //Format24bppRgb; // 24 बिट प्रति पिक्सेल, RGB।
>      //Format32bppArgb; // 32 बिट प्रति पिक्सेल, ARGB।
> 
>      // निर्दिष्ट छवि आकार के साथ प्रस्तुति को TIFF के रूप में सहेजें
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | डिफ़ॉल्ट कंस्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [getImageSize()](#getImageSize--) | उत्पन्न TIFF छवि का आकार निर्धारित करता है। |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | उत्पन्न TIFF छवि का आकार निर्धारित करता है। |
| [getDpiX()](#getDpiX--) | क्षैतिज रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। |
| [setDpiX(long value)](#setDpiX-long-) | क्षैतिज रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। |
| [getDpiY()](#getDpiY--) | ऊर्ध्वाधर रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। |
| [setDpiY(long value)](#setDpiY-long-) | ऊर्ध्वाधर रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। |
| [getCompressionType()](#getCompressionType--) | संपीड़न प्रकार निर्धारित करता है। |
| [setCompressionType(int value)](#setCompressionType-int-) | संपीड़न प्रकार निर्धारित करता है। |
| [getPixelFormat()](#getPixelFormat--) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। |
| [setPixelFormat(int value)](#setPixelFormat-int-) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getBwConversionMode()](#getBwConversionMode--) | रंगीन छवि को काले-सफ़ेद छवि में बदलने के एल्गोरिद्म को निर्धारित करता है। |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | रंगीन छवि को काले-सफ़ेद छवि में बदलने के एल्गोरिद्म को निर्धारित करता है। |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


डिफ़ॉल्ट कंस्ट्रक्टर।

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने-योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**वापसी:**
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

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```


उत्पन्न TIFF छवि का आकार निर्धारित करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किए जाएंगे। पढ़ें/लिखें java.awt.Dimension।

**वापसी:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```


उत्पन्न TIFF छवि का आकार निर्धारित करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किए जाएंगे। पढ़ें/लिखें java.awt.Dimension।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


क्षैतिज रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। पढ़ें/लिखें long।

**वापसी:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


क्षैतिज रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


ऊर्ध्वाधर रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। पढ़ें/लिखें long।

**वापसी:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


ऊर्ध्वाधर रिज़ॉल्यूशन को डॉट्स प्रति इंच में निर्धारित करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


संपीड़न प्रकार निर्धारित करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**वापसी:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


संपीड़न प्रकार निर्धारित करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

**वापसी:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
public final int getBwConversionMode()
```


रंगीन छवि को काले-सफ़ेद छवि में बदलने के एल्गोरिद्म को निर्धारित करता है। यह विकल्प केवल तब लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट हो। पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)।

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
public final void setBwConversionMode(int value)
```


रंगीन छवि को काले-सफ़ेद छवि में बदलने के एल्गोरिद्म को निर्धारित करता है। यह विकल्प केवल तब लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट हो। पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)।

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