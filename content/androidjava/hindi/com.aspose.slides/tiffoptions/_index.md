---
title: TiffOptions
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक प्रस्तुति को TIFF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
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

एक प्रस्तुति को TIFF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // एक Presentation ऑब्जेक्ट को इंस्टैंटिएट करता है जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // प्रस्तुति को TIFF दस्तावेज़ में सहेजा जा रहा है
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // एक Presentation ऑब्जेक्ट को इंस्टैंटिएट करता है जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // TiffOptions क्लास को इंस्टैंटिएट करता है
>      TiffOptions opts = new TiffOptions();
>      // संपीड़न प्रकार सेट किया जा रहा है
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // संपीड़न प्रकार
>      // Default - डिफ़ॉल्ट संपीड़न योजना (LZW) निर्धारित करता है।
>      // None - कोई संपीड़न नहीं निर्धारित करता है।
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // गहराई संपीड़न प्रकार पर निर्भर करती है और मैन्युअल रूप से सेट नहीं की जा सकती।
>      // रिज़ॉल्यूशन यूनिट हमेशा 2 (डॉट्स प्रति इंच) के बराबर होता है
>      // इमेज DPI सेट किया जा रहा है
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // इमेज आकार सेट करें
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // निर्दिष्ट इमेज आकार के साथ प्रस्तुति को TIFF में सहेजें
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // एक Presentation ऑब्जेक्ट को इंस्टैंटिएट करता है जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat में निम्न मान शामिल हैं (जैसा कि दस्तावेज़ीकरण से देखा जा सकता है):
>      //Format1bppIndexed; // 1 बिट प्रति पिक्सेल, अनुक्रमित।
>      //Format4bppIndexed; // 4 बिट प्रति पिक्सेल, अनुक्रमित।
>      //Format8bppIndexed; // 8 बिट प्रति पिक्सेल, अनुक्रमित।
>      //Format24bppRgb; // 24 बिट प्रति पिक्सेल, RGB।
>      //Format32bppArgb; // 32 बिट प्रति पिक्सेल, ARGB।
> 
>      // निर्दिष्ट इमेज आकार के साथ प्रस्तुति को TIFF में सहेजें
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | डिफ़ॉल्ट कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। |
| [getImageSize()](#getImageSize--) | उत्पन्न TIFF इमेज का आकार निर्धारित करता है। |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | उत्पन्न TIFF इमेज का आकार निर्धारित करता है। |
| [getDpiX()](#getDpiX--) | डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्धारित करता है। |
| [setDpiX(long value)](#setDpiX-long-) | डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्धारित करता है। |
| [getDpiY()](#getDpiY--) | डॉट्स प्रति इंच में लंबवत रेज़ोल्यूशन निर्धारित करता है। |
| [setDpiY(long value)](#setDpiY-long-) | डॉट्स प्रति इंच में लंबवत रेज़ोल्यूशन निर्धारित करता है। |
| [getCompressionType()](#getCompressionType--) | कम्प्रेशन प्रकार निर्धारित करता है। |
| [setCompressionType(int value)](#setCompressionType-int-) | कम्प्रेशन प्रकार निर्धारित करता है। |
| [getPixelFormat()](#getPixelFormat--) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। |
| [setPixelFormat(int value)](#setPixelFormat-int-) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रस्तुति निर्यात की जा रही हो [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रस्तुति निर्यात की जा रही हो [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getBwConversionMode()](#getBwConversionMode--) | रंगीन छवि को काले और सफेद छवि में बदलने के एल्गोरिदम को निर्धारित करता है। |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | रंगीन छवि को काले और सफेद छवि में बदलने के एल्गोरिदम को निर्धारित करता है। |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

डिफ़ॉल्ट कंस्ट्रक्टर।

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट false है।

**रिटर्न:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

उत्पन्न TIFF इमेज का आकार निर्धारित करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किया जाएगा। पढ़ें/लिखें [Size](../../com.aspose.slides.android/size)।

**रिटर्न:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

उत्पन्न TIFF इमेज का आकार निर्धारित करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किया जाएगा। पढ़ें/लिखें [Size](../../com.aspose.slides.android/size)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्धारित करता है। पढ़ें/लिखें long।

**रिटर्न:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्धारित करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

डॉट्स प्रति इंच में लंबवत रेज़ोल्यूशन निर्धारित करता है। पढ़ें/लिखें long।

**रिटर्न:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

डॉट्स प्रति इंच में लंबवत रेज़ोल्यूशन निर्धारित करता है। पढ़ें/लिखें long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

कम्प्रेशन प्रकार निर्धारित करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**रिटर्न:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

कम्प्रेशन प्रकार निर्धारित करता है। पढ़ें/लिखें [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्धारित करता है। पढ़ें/लिखें [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)।

**रिटर्न:**
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

स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रस्तुति निर्यात की जा रही हो [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रस्तुति निर्यात की जा रही हो [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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

रंगीन छवि को काले और सफेद छवि में बदलने के एल्गोरिदम को निर्धारित करता है। यह विकल्प केवल तब लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट हो। पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default) है।

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
public final void setBwConversionMode(int value)
```

रंगीन छवि को काले और सफेद छवि में बदलने के एल्गोरिदम को निर्धारित करता है। यह विकल्प केवल तब लागू होगा जब CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) या [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) पर सेट हो। पढ़ें/लिखें [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)। डिफ़ॉल्ट [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default) है।

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