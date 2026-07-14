---
title: PdfOptions
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक प्रस्तुति को PDF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

एक प्रस्तुति को Pdf प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions वर्ग का उदाहरण बनाता है
>      PdfOptions pdfOptions = new PdfOptions();
>      // Jpeg गुणवत्ता सेट करता है
>      pdfOptions.setJpegQuality((byte)90);
>      // मेटा फ़ाइलों के लिए व्यवहार सेट करता है
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // टेक्स्ट संपीड़न स्तर सेट करता है
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // PDF मानक को परिभाषित करता है
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // प्रस्तुति को PDF के रूप में सहेजता है
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // एक Presentation वर्ग का उदाहरण बनाता है जो PowerPoint फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions वर्ग का उदाहरण बनाता है
>      PdfOptions pdfOptions = new PdfOptions();
>      // छिपी स्लाइड्स जोड़ता है
>      pdfOptions.setShowHiddenSlides(true);
>      // प्रस्तुति को PDF के रूप में सहेजता है
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // एक Presentation ऑब्जेक्ट बनाता है जो PowerPoint फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions वर्ग का उदाहरण बनाता है
>      PdfOptions pdfOptions = new PdfOptions();
>      // PDF पासवर्ड और एक्सेस अनुमतियाँ सेट करता है
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // प्रस्तुति को PDF के रूप में सहेजता है
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // स्लाइड प्रकार और आकार सेट करना
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | डिफ़ॉल्ट निर्माता। |
## विधियां

| विधि | विवरण |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में इंक वस्तुओं की दृश्यता को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [getTextCompression()](#getTextCompression--) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्धारित करता है। |
| [setTextCompression(int value)](#setTextCompression-int-) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्धारित करता है। |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वचालित रूप से चयन करने के बारे में संकेत देता है। |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वचालित रूप से चयन करने के बारे में संकेत देता है। |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं। |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं। |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides को सामान्य मानने के लिए फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी को प्राप्त या सेट करता है। |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides को सामान्य मानने के लिए फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी को प्राप्त या सेट करता है। |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँगे या केवल उपयोग किया गया उपसमुच्चय। |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँगे या केवल उपयोग किया गया उपसमुच्चय। |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजने के बारे में संकेत देता है। |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजने के बारे में संकेत देता है। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान प्राप्त या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान प्राप्त या सेट करता है। |
| [getCompliance()](#getCompliance--) | उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। |
| [setCompliance(int value)](#setCompliance-int-) | उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। |
| [getPassword()](#getPassword--) | PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [getAccessPermissions()](#getAccessPermissions--) | दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलने पर कौन से एक्सेस अनुमतियाँ प्रदान की जाएँगी, इसे निर्दिष्ट करने वाले फ़्लैग का एक सेट शामिल करता है। |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलने पर कौन से एक्सेस अनुमतियाँ प्रदान की जाएँगी, इसे निर्दिष्ट करने वाले फ़्लैग का एक सेट शामिल करता है। |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | प्रस्तुति में उपयोग किए गए सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए सही। |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | प्रस्तुति में उपयोग किए गए सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए सही। |
| [getSufficientResolution()](#getSufficientResolution--) | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान प्राप्त या सेट करता है। |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान प्राप्त या सेट करता है। |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए सही। |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए सही। |
| [getImageTransparentColor()](#getImageTransparentColor--) | छवि के ट्रांसपेरेंट रंग को प्राप्त या सेट करता है। |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | छवि के ट्रांसपेरेंट रंग को प्राप्त या सेट करता है। |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | यदि सही है तो निर्दिष्ट ट्रांसपेरेंट रंग को छवि पर लागू करता है। |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | यदि सही है तो निर्दिष्ट ट्रांसपेरेंट रंग को छवि पर लागू करता है। |
| [getIncludeOleData()](#getIncludeOleData--) | प्रस्तुति से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए सही। |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | प्रस्तुति से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए सही। |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

डिफ़ॉल्ट निर्माता।

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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

जब प्रस्तुति निर्यात की जाती है तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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

निर्यात किए गए दस्तावेज़ में इंक वस्तुओं की दृश्यता को नियंत्रित करने वाले विकल्प प्रदान करता है। **केवल-पढ़ने योग्य** [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट **गलत** है।

**रिटर्न:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट **गलत** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्धारित करता है। **पढ़ने/लिखने योग्य** [PdfTextCompression](../../com.aspose.slides/pdftextcompression)।

--------------------

डिफ़ॉल्ट **[PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)** है।

**रिटर्न:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्धारित करता है। **पढ़ने/लिखने योग्य** [PdfTextCompression](../../com.aspose.slides/pdftextcompression)।

--------------------

डिफ़ॉल्ट **[PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वचालित रूप से चयन करने के बारे में संकेत देता है। यदि सही सेट किया जाता है, तो प्रस्तुति में प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा।

--------------------

सबसे अच्छा छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से **गलत** है।

--------------------

डिफ़ॉल्ट **गलत** है।

**रिटर्न:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वचालित रूप से चयन करने के बारे में संकेत देता है। यदि सही सेट किया जाता है, तो प्रस्तुति में प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा।

--------------------

सबसे अच्छा छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से **गलत** है।

--------------------

डिफ़ॉल्ट **गलत** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं। कोड 127 से अधिक वाले अक्षर हमेशा एम्बेड होते हैं। सामान्य फ़ॉन्ट सूची में PDF के बेस 14 फ़ॉन्ट और अतिरिक्त उपयोगकर्ता-निर्दिष्ट फ़ॉन्ट शामिल हैं। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **सही** है।

**रिटर्न:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं। कोड 127 से अधिक वाले अक्षर हमेशा एम्बेड होते हैं। सामान्य फ़ॉन्ट सूची में PDF के बेस 14 फ़ॉन्ट और अतिरिक्त उपयोगकर्ता-निर्दिष्ट फ़ॉन्ट शामिल हैं। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **सही** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides को सामान्य मानने के लिए फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी को प्राप्त या सेट करता है। **पढ़ने/लिखने योग्य** String[]।

**रिटर्न:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides को सामान्य मानने के लिए फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी को प्राप्त या सेट करता है। **पढ़ने/लिखने योग्य** String[]।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँगे या केवल उपयोग किया गया उपसमुच्चय। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **गलत** है।

**रिटर्न:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँगे या केवल उपयोग किया गया उपसमुच्चय। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **गलत** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजने के बारे में संकेत देता है। यह दृष्टिकोण कुछ फ़ॉन्ट के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **गलत** है।

**रिटर्न:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजने के बारे में संकेत देता है। यह दृष्टिकोण कुछ फ़ॉन्ट के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **गलत** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता को निर्धारित करने वाला मान प्राप्त या सेट करता है। **पढ़ने/लिखने योग्य** byte।

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियाँ हों।

PDF प्रारूप में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता सेट या प्राप्त करने के लिए इस गुण का उपयोग करें। मान 0 से 100 तक हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **100** है।

**रिटर्न:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता को निर्धारित करने वाला मान प्राप्त या सेट करता है। **पढ़ने/लिखने योग्य** byte।

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियाँ हों।

PDF प्रारूप में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता सेट या प्राप्त करने के लिए इस गुण का उपयोग करें। मान 0 से 100 तक हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **100** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public 



Sorry, 

The 



...



...



 

The ...



...







```

उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। **पढ़ने/लिखने योग्य** [PdfCompliance](../../com.aspose.slides/pdfcompliance)।

--------------------

डिफ़ॉल्ट **[PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)** है।

**रिटर्न:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। **पढ़ने/लिखने योग्य** [PdfCompliance](../../com.aspose.slides/pdfcompliance)।

--------------------

डिफ़ॉल्ट **[PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। **पढ़ने/लिखने योग्य** String।

**रिटर्न:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। **पढ़ने/लिखने योग्य** String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलने पर कौन से एक्सेस अनुमतियाँ प्रदान की जाएँगी, इसे निर्दिष्ट करने वाले फ़्लैग का एक सेट शामिल करता है। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)।

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलने पर कौन से एक्सेस अनुमतियाँ प्रदान की जाएँगी, इसे निर्धारित करने वाले फ़्लैग का एक सेट शामिल करता है। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)।

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

प्रस्तुति में उपयोग की गई सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए सही। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **सही** है। PDF दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों दोनों को शामिल कर सकता है। यदि SaveMetafilesAsPng को सही सेट किया जाता है तो स्रोत मेटा-फ़ाइल छवि PNG रूप में परिवर्तित होकर PDF में रास्टर छवि के रूप में सहेजी जाती है। यदि SaveMetafilesAsPng को गलत सेट किया जाता है तो स्रोत मेटा-फ़ाइल PDF वेक्टर ग्राफ़िक्स में परिवर्तित होती है। प्रत्येक दृष्टिकोण के अपने फायदे और नुक़सान हैं। उदाहरण के लिए, यदि मेटा-फ़ाइल PNG में बदली जाती है, तो परिणामस्वरूप दस्तावेज़ के स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि मेटा-फ़ाइल PDF वेक्टर ग्राफ़िक्स में बदली जाती है, तो PDF व्यूअर टूल में प्रदर्शन समस्याएँ हो सकती हैं।

**रिटर्न:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

प्रस्तुति में उपयोग की गई सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए सही। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **सही** है। PDF दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों दोनों को शामिल कर सकता है। यदि SaveMetafilesAsPng को सही सेट किया जाता है तो स्रोत मेटा-फ़ाइल छवि PNG रूप में परिवर्तित होकर PDF में रास्टर छवि के रूप में सहेजी जाती है। यदि SaveMetafilesAsPng को गलत सेट किया जाता है तो स्रोत मेटा-फ़ाइल PDF वेक्टर ग्राफ़िक्स में परिवर्तित होती है। प्रत्येक दृष्टिकोण के अपने फायदे और नुक़सान हैं। उदाहरण के लिए, यदि मेटा-फ़ाइल PNG में बदली जाती है, तो परिणामस्वरूप दस्तावेज़ के स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि मेटा-फ़ाइल PDF वेक्टर ग्राफ़िक्स में बदली जाती है, तो PDF व्यूअर टूल में प्रदर्शन समस्याएँ हो सकती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान प्राप्त या सेट करता है। **पढ़ने/लिखने योग्य** float।

मान: इस पैरामीटर का प्रभाव कुछ कारकों पर निर्भर करता है। एल्गोरिद्म प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के अनुसार सर्वोत्तम आउटपुट छवि आकार प्राप्त करने का प्रयास करता है। समान प्रॉपर्टी मानों का उपयोग करने से समान परिणाम मिल सकता है। दृश्य प्रभाव पाने के लिए कदम 16 या 32 का उपयोग करने की सलाह दी जाती है।

--------------------

प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**रिटर्न:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान प्राप्त या सेट करता है। **पढ़ने/लिखने योग्य** float।

मान: इस पैरामीटर का प्रभाव कुछ कारकों पर निर्भर करता है। एल्गोरिद्म प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के अनुसार सर्वोत्तम आउटपुट छवि आकार प्राप्त करने का प्रयास करता है। समान प्रॉपर्टी मानों का उपयोग करने से समान परिणाम मिल सकता है। दृश्य प्रभाव पाने के लिए कदम 16 या 32 का उपयोग करने की सलाह दी जाती है।

--------------------

प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए सही। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **गलत** है।

**रिटर्न:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए सही। **पढ़ने/लिखने योग्य** boolean।

--------------------

डिफ़ॉल्ट **गलत** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

छवि के ट्रांसपेरेंट रंग को प्राप्त या सेट करता है।

मान: छवि के ट्रांसपेरेंट रंग का मान।

**रिटर्न:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

छवि के ट्रांसपेरेंट रंग को प्राप्त या सेट करता है।

मान: छवि के ट्रांसपेरेंट रंग का मान।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

यदि सही है तो निर्दिष्ट ट्रांसपेरेंट रंग को छवि पर लागू करता है।

**रिटर्न:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

यदि सही है तो निर्दिष्ट ट्रांसपेरेंट रंग को छवि पर लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

प्रस्तुति से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए सही। **पढ़ने/लिखने योग्य**  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट **गलत** है।

**रिटर्न:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

प्रस्तुति से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए सही। **पढ़ने/लिखने योग्य**  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट **गलत** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |