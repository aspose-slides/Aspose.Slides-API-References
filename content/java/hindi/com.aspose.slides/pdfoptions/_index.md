---
title: PdfOptions
second_title: Aspose.Slides for Java API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को Pdf स्वरूप में कैसे सहेजा जाए।
type: docs
url: /hi/com.aspose.slides/pdfoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**  
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
>      // मेटा फ़ाइलों के व्यवहार को सेट करता है
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // पाठ संपीड़न स्तर सेट करता है
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // PDF मानक निर्धारित करता है
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // प्रस्तुति को PDF के रूप में सहेजता है
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // PowerPoint फ़ाइल को दर्शाने वाली Presentation वर्ग का उदाहरण बनाता है
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
>  // PowerPoint फ़ाइल को दर्शाने वाला Presentation ऑब्जेक्ट बनाता है
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions वर्ग का उदाहरण बनाता है
>      PdfOptions pdfOptions = new PdfOptions();
>      // PDF पासवर्ड और एक्सेस अनुमतियां सेट करता है
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
>  // एक प्रस्तुति फ़ाइल को दर्शाने वाला Presentation ऑब्जेक्ट बनाता है
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

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | डिफ़ॉल्ट कंस्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्मित दस्तावेज़ में छिपी स्लाइड्स को शामिल करना है या नहीं, निर्दिष्ट करता है। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्मित दस्तावेज़ में छिपी स्लाइड्स को शामिल करना है या नहीं, निर्दिष्ट करता है। |
| [getTextCompression()](#getTextCompression--) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग होने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [setTextCompression(int value)](#setTextCompression-int-) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग होने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | स्वतः प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) चुनना चाहिए या नहीं, संकेत करता है। |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | स्वतः प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) चुनना चाहिए या नहीं, संकेत करता है। |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट्स एम्बेड करेगा या नहीं निर्धारित करता है। |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट्स एम्बेड करेगा या नहीं निर्धारित करता है। |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | उपयोगकर्ता द्वारा परिभाषित फ़ॉन्ट परिवारों के नामों की एक एरे लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | उपयोगकर्ता द्वारा परिभाषित फ़ॉन्ट परिवारों के नामों की एक एरे लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | फ़ॉन्ट के सभी अक्षरों को एम्बेड करना है या केवल उपयोग किए गए उपसमुह को, निर्धारित करता है। |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | फ़ॉन्ट के सभी अक्षरों को एम्बेड करना है या केवल उपयोग किए गए उपसमुह को, निर्धारित करता है। |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता हो तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं संकेत करता है। |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता हो तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं संकेत करता है। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है। |
| [getCompliance()](#getCompliance--) | जनरेटेड PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। |
| [setCompliance(int value)](#setCompliance-int-) | जनरेटेड PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। |
| [getPassword()](#getPassword--) | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [getAccessPermissions()](#getAccessPermissions--) | जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | एक प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलने के लिए true। |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | एक प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलने के लिए true। |
| [getSufficientResolution()](#getSufficientResolution--) | PDF दस्तावेज़ में छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है। |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF दस्तावेज़ में छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है। |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true। |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true। |
| [getImageTransparentColor()](#getImageTransparentColor--) | छवि के पारदर्शी रंग को प्राप्त या सेट करता है। |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | छवि के पारदर्शी रंग को प्राप्त या सेट करता है। |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [getIncludeOleData()](#getIncludeOleData--) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

डिफ़ॉल्ट कंस्ट्रक्टर।

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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

**वापसी:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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

निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्मित दस्तावेज़ में छिपी स्लाइड्स को शामिल करना है या नहीं, निर्दिष्ट करता है। डिफ़ॉल्ट false है।

**वापसी:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्मित दस्तावेज़ में छिपी स्लाइड्स को शामिल करना है या नहीं, निर्दिष्ट करता है। डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग होने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PdfTextCompression](../../com.aspose.slides/pdftextcompression)।

--------------------

डिफ़ॉल्ट [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate) है।

**वापसी:**  
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग होने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PdfTextCompression](../../com.aspose.slides/pdftextcompression)।

--------------------

डिफ़ॉल्ट [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate) है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

स्वतः प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) चुनना चाहिए या नहीं, संकेत करता है। यदि true पर सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिये सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा रहेगा।

--------------------

सबसे अच्छा छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM लेता है, यह विकल्प डिफ़ॉल्ट रूप से false है।

--------------------

डिफ़ॉल्ट false है।

**वापसी:**  
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

स्वतः प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) चुनना चाहिए या नहीं, संकेत करता है। यदि true पर सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिये सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा रहेगा।

--------------------

सबसे अच्छा छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM लेता है, यह विकल्प डिफ़ॉल्ट रूप से false है।

--------------------

डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट्स एम्बेड करेगा या नहीं निर्धारित करता है। 127 से बड़े कोड के फ़ॉन्ट्स हमेशा एम्बेडेड होते हैं। सामान्य फ़ॉन्ट सूची में PDF की बेस 14 फ़ॉन्ट्स और अतिरिक्त उपयोगकर्ता-निर्दिष्ट फ़ॉन्ट्स शामिल हैं। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **true** है।

**वापसी:**  
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Aspose.Slides ASCII (33..127 कोड रेंज) पाठ के लिए सामान्य फ़ॉन्ट्स एम्बेड करेगा या नहीं निर्धारित करता है। 127 से बड़े कोड के फ़ॉन्ट्स हमेशा एम्बेडेड होते हैं। सामान्य फ़ॉन्ट सूची में PDF की बेस 14 फ़ॉन्ट्स और अतिरिक्त उपयोगकर्ता-निर्दिष्ट फ़ॉन्ट्स शामिल हैं। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **true** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

उपयोगकर्ता द्वारा परिभाषित फ़ॉन्ट परिवारों के नामों की एक एरे लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। पढ़ें/लिखें String[]।

**वापसी:**  
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

उपयोगकर्ता द्वारा परिभाषित फ़ॉन्ट परिवारों के नामों की एक एरे लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। पढ़ें/लिखें String[]।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

फ़ॉन्ट के सभी अक्षरों को एम्बेड करना है या केवल उपयोग किए गए उपसमुह को, निर्धारित करता है। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **false** है।

**वापसी:**  
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

फ़ॉन्ट के सभी अक्षरों को एम्बेड करना है या केवल उपयोग किए गए उपसमुह को, निर्धारित करता है। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **false** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

यदि फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता हो तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं संकेत करता है। यह दृष्टिकोण कुछ फ़ॉन्ट्स के लिये परिणामी PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **false** है।

**वापसी:**  
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

यदि फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता हो तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं संकेत करता है। यह दृष्टिकोण कुछ फ़ॉन्ट्स के लिये परिणामी PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **false** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है। पढ़ें/लिखें byte।

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियां हों।

PDF प्रारूप में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता को प्राप्त या सेट करने के लिये इस गुण का उपयोग करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 सबसे खराब गुणवत्ता पर अधिकतम संपीड़न और 100 सबसे अच्छी गुणवत्ता पर न्यूनतम संपीड़न को दर्शाता है।

डिफ़ॉल्ट मान **100** है।

**वापसी:**  
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है। पढ़ें/लिखें byte।

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियां हों।

PDF प्रारूप में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता को प्राप्त या सेट करने के लिये इस गुण का उपयोग करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 सबसे खराब गुणवत्ता पर अधिकतम संपीड़न और 100 सबसे अच्छी गुणवत्ता पर न्यूनतम संपीड़न को दर्शाता है।

डिफ़ॉल्ट मान **100** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

जनरेटेड PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। पढ़ें/लिखें [PdfCompliance](../../com.aspose.slides/pdfcompliance)।

--------------------

डिफ़ॉल्ट [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17) है।

**वापसी:**  
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

जनरेटेड PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। पढ़ें/लिखें [PdfCompliance](../../com.aspose.slides/pdfcompliance)।

--------------------

डिफ़ॉल्ट [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17) है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String।

**वापसी:**  
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)।

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


**वापसी:**  
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)।

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

एक प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलने के लिए true। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **true** है। PDF दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों दोनों को समायोजित कर सकता है। यदि SaveMetafilesAsPng true पर सेट किया जाता है तो स्रोत Metafile छवि PNG प्रारूप में बदलकर PDF में रास्टर छवि के रूप में सहेजी जाती है। यदि SaveMetafilesAsPng false पर सेट किया जाता है तो स्रोत Metafile को PDF वेक्टर ग्राफ़िक्स में बदल दिया जाता है। प्रत्येक दृष्टिकोण के अपने लाभ और हानि हैं। उदाहरण के लिये, यदि Metafile को PNG में बदल दिया जाता है तो परिणामस्वरूप दस्तावेज़ स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि Metafile को PDF वेक्टर ग्राफ़िक्स में बदल दिया जाता है तो PDF व्यूअर टूल में प्रदर्शन संबंधी समस्याएँ हो सकती हैं।

**वापसी:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

एक प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलने के लिए true। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **true** है। PDF दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों दोनों को समायोजित कर सकता है। यदि SaveMetafilesAsPng true पर सेट किया जाता है तो स्रोत Metafile छवि PNG प्रारूप में बदलकर PDF में रास्टर छवि के रूप में सहेजी जाती है। यदि SaveMetafilesAsPpng false पर सेट किया जाता है तो स्रोत Metafile को PDF वेक्टर ग्राफ़िक्स में बदल दिया जाता है। प्रत्येक दृष्टिकोण के अपने लाभ और हानि हैं। उदाहरण के लिये, यदि Metafile को PNG में बदल दिया जाता है तो परिणामस्वरूप दस्तावेज़ स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि Metafile को PDF वेक्टर ग्राफ़िक्स में बदल दिया जाता है तो PDF व्यूअर टूल में प्रदर्शन संबंधी समस्याएँ हो सकती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

PDF दस्तावेज़ में छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है। पढ़ें/लिखें float।

मान: इस पैरामीटर का प्रभाव कई कारकों पर निर्भर करता है। एल्गोरिद्म प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के आधार पर सर्वोत्तम आउटपुट छवि आकार प्राप्त करने का प्रयास करता है। समान प्रॉपर्टी मानों का उपयोग करने पर समान परिणाम मिल सकते हैं। दृश्य प्रभाव पाने के लिये चरण 16 या 32 उपयोग करने की सलाह दी जाती है।

--------------------

यह प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**वापसी:**  
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

PDF दस्तावेज़ में छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है। पढ़ें/लिखें float।

मान: इस पैरामीटर का प्रभाव कई कारकों पर निर्भर करता है। एल्गोरिद्म प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के आधार पर सर्वोत्तम आउटपुट छवि आकार प्राप्त करने का प्रयास करता है। समान प्रॉपर्टी मानों का उपयोग करने पर समान परिणाम मिल सकते हैं। दृश्य प्रभाव पाने के लिये चरण 16 या 32 उपयोग करने की सलाह दी जाती है।

--------------------

यह प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **false** है।

**वापसी:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true। पढ़ें/लिखें boolean।

--------------------

डिफ़ॉल्ट **false** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

छवि के पारदर्शी रंग को प्राप्त या सेट करता है।

मान: छवि के पारदर्शी रंग का मान।

**वापसी:**  
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

छवि के पारदर्शी रंग को प्राप्त या सेट करता है।

मान: छवि के पारदर्शी रंग का मान।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है।

**वापसी:**  
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें boolean।

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

डिफ़ॉल्ट **false** है।

**वापसी:**  
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें boolean।

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

डिफ़ॉल्ट **false** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |