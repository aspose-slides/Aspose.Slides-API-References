---
title: IPdfOptions
second_title: Aspose.Slides for Android के लिये Java API संदर्भ
description: प्रस्तुति को PDF स्वरूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/ipdfoptions/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

एक प्रस्तुति को PDF स्वरूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [setTextCompression(int value)](#setTextCompression-int-) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयन किया जाना चाहिए या नहीं। |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयन किया जाना चाहिए या नहीं। |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII अक्षर 32-127 के लिए true type फ़ॉन्ट एम्बेड करने के लिए true। |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII अक्षर 32-127 के लिए true type फ़ॉन्ट एम्बेड करने के लिए true। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides द्वारा सामान्य माने जाने वाले फ़ॉन्ट फ़ैमिली के उपयोगकर्ता-परिभाषित नामों की एक एरे को लौटाता या सेट करता है। |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षरों को एम्बेड किया जाना चाहिए या केवल उपयोग किए गए उपसमुच्चय को। |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षरों को एम्बेड किया जाना चाहिए या केवल उपयोग किए गए उपसमुच्चय को। |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है, तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ किया जाए और PDF में सहेजा जाए, यह दर्शाता है। |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है, तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ किया जाए और PDF में सहेजा जाए, यह दर्शाता है। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। |
| [getCompliance()](#getCompliance--) | उत्पन्न PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। |
| [setCompliance(int value)](#setCompliance-int-) | उत्पन्न PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। |
| [getPassword()](#getPassword--) | PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [getAccessPermissions()](#getAccessPermissions--) | जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | प्रस्तुति में उपयोग किए गए सभी मीटाफाइल्स को PNG छवियों में परिवर्तित करने के लिए true। |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | प्रस्तुति में उपयोग किए गए सभी मीटाफाइल्स को PNG छवियों में परिवर्तित करने के लिए true। |
| [getSufficientResolution()](#getSufficientResolution--) | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाले मान को लौटाता या सेट करता है। |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाले मान को लौटाता या सेट करता है। |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | प्रत्येक स्लाइड के चारों ओर काली फ़्रेम खींचने के लिए true। |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | प्रत्येक स्लाइड के चारों ओर काली फ़्रेम खींचने के लिए true। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [getImageTransparentColor()](#getImageTransparentColor--) | छवि की पारदर्शी रंग को प्राप्त करता या सेट करता है। |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | छवि की पारदर्शी रंग को प्राप्त करता या सेट करता है। |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [getInkOptions()](#getInkOptions--) | निर्यातित दस्तावेज़ में इंक वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getIncludeOleData()](#getIncludeOleData--) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

डिफ़ॉल्ट है [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**वापसी:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

डिफ़ॉल्ट है [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयन किया जाना चाहिए या नहीं। यदि true सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे परिणामस्वरूप PDF दस्तावेज़ का आकार छोटा होगा।

--------------------

सबसे अच्छा छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM लेता है, और यह विकल्प डिफ़ॉल्ट रूप से false है।

--------------------

डिफ़ॉल्ट है false.

**वापसी:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयन किया जाना चाहिए या नहीं। यदि true सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे परिणामस्वरूप PDF दस्तावेज़ का आकार छोटा होगा।

--------------------

सबसे अच्छा छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM लेता है, और यह विकल्प डिफ़ॉल्ट रूप से false है।

--------------------

डिफ़ॉल्ट है false.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

ASCII अक्षर 32-127 के लिए true type फ़ॉन्ट एम्बेड करने के लिए true। 127 से बड़े अक्षर कोड के फ़ॉन्ट हमेशा एम्बेड किए जाते हैं। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**.

**वापसी:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

ASCII अक्षर 32-127 के लिए true type फ़ॉन्ट एम्बेड करने के लिए true। 127 से बड़े अक्षर कोड के फ़ॉन्ट हमेशा एम्बेड किए जाते हैं। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट है false.

**वापसी:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट है false.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides द्वारा सामान्य माने जाने वाले फ़ॉन्ट फ़ैमिली के उपयोगकर्ता-परिभाषित नामों की एक एरे को लौटाता या सेट करता है। पढ़ें/लिखें String[].

**वापसी:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides द्वारा सामान्य माने जाने वाले फ़ॉन्ट फ़ैमिली के उपयोगकर्ता-परिभाषित नामों की एक एरे को लौटाता या सेट करता है। पढ़ें/लिखें String[].

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

निर्धारित करता है कि फ़ॉन्ट के सभी अक्षरों को एम्बेड किया जाना चाहिए या केवल उपयोग किए गए उपसमुच्चय को। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**वापसी:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

निर्धारित करता है कि फ़ॉन्ट के सभी अक्षरों को एम्बेड किया जाना चाहिए या केवल उपयोग किए गए उपसमुच्चय को। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है, तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ किया जाए और PDF में सहेजा जाए, यह दर्शाता है। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता बढ़ा सकता है। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**वापसी:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है, तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ किया जाए और PDF में सहेजा जाए, यह दर्शाता है। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता बढ़ा सकता है। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

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

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियां हों।

इस प्रॉपर्टी का उपयोग PDF स्वरूप में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता प्राप्त करने या सेट करने के लिए करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **100** है।

**वापसी:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता या सेट करता है। पढ़ें/लिखें byte.

--------------------

केवल तब प्रभावी जब दस्तावेज़ में JPEG छवियां हों।

इस प्रॉपर्टी का उपयोग PDF स्वरूप में सहेजते समय दस्तावेज़ के भीतर छवियों की गुणवत्ता प्राप्त करने या सेट करने के लिए करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **100** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

उत्पन्न PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। पढ़ें/लिखें [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

डिफ़ॉल्ट है [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**वापसी:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

उत्पन्न PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। पढ़ें/लिखें [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

डिफ़ॉल्ट है [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String.

**वापसी:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स के एक सेट को शामिल करता है। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स के एक सेट को शामिल करता है। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

प्रस्तुति में उपयोग किए गए सभी मीटाफाइल्स को PNG छवियों में परिवर्तित करने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**। PDF दस्तावेज़ वेक्टर ग्राफिक्स और रास्टर छवियों को शामिल कर सकता है। यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत मीटाफाइल छवि को Png प्रारूप में परिवर्तित किया जाता है और PDF में रास्टर छवि के रूप में सहेजा जाता है। यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत मीटाफाइल को PDF वेक्टर ग्राफिक्स में बदल दिया जाता है। प्रत्येक दृष्टिकोण के अपने फायदे और नुकसान होते हैं। उदाहरण के लिए, यदि मीटाफाइल को PNG में परिवर्तित किया जाता है, तो परिणामस्वरूप दस्तावेज़ स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि मीटाफाइल को PDF वेक्टर ग्राफिक्स में परिवर्तित किया जाता है, तो PDF व्यूइंग टूल में प्रदर्शन समस्याएं उत्पन्न हो सकती हैं।

**वापसी:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

प्रस्तुति में उपयोग किए गए सभी मीटाफाइल्स को PNG छवियों में परिवर्तित करने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**। PDF दस्तावेज़ वेक्टर ग्राफिक्स और रास्टर छवियों को शामिल कर सकता है। यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत मीटाफाइल छवि को Png प्रारूप में परिवर्तित किया जाता है और PDF में रास्टर छवि के रूप में सहेजा जाता है। यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत मीटाफाइल को PDF वेक्टर ग्राफिक्स में बदल दिया जाता है। प्रत्येक दृष्टिकोण के अपने फायदे और नुकसान होते हैं। उदाहरण के लिए, यदि मीटाफाइल को PNG में परिवर्तित किया जाता है, तो परिणामस्वरूप दस्तावेज़ स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि मीटाफाइल को PDF वेक्टर ग्राफिक्स में परिवर्तित किया जाता है, तो PDF व्यूइंग टूल में प्रदर्शन समस्याएं उत्पन्न हो सकती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाले मान को लौटाता या सेट करता है। पढ़ें/लिखें float.

मान: इस पैरामीटर का प्रभाव कुछ कारकों पर निर्भर करता है। एल्गोरिदम प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के आधार पर सर्वोत्तम आउटपुट छवि आकार प्राप्त करने की कोशिश करता है। समान प्रॉपर्टी मानों का उपयोग करने से समान परिणाम मिल सकता है। दृश्यमान प्रभाव के लिए चरण 16 या 32 का उपयोग करने की अनुशंसा की जाती है।

प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**वापसी:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाले मान को लौटाता या सेट करता है। पढ़ें/लिखें float.

मान: इस पैरामीटर का प्रभाव कुछ कारकों पर निर्भर करता है। एल्गोरिदम प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के आधार पर सर्वोत्तम आउटपुट छवि आकार प्राप्त करने की कोशिश करता है। समान प्रॉपर्टी मानों का उपयोग करने से समान परिणाम मिल सकता है। दृश्यमान प्रभाव के लिए चरण 16 या 32 का उपयोग करने की अनुशंसा की जाती है।

प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

प्रत्येक स्लाइड के चारों ओर काली फ़्रेम खींचने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**वापसी:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

प्रत्येक स्लाइड के चारों ओर काली फ़्रेम खींचने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

छवि की पारदर्शी रंग को प्राप्त करता या सेट करता है।

मान: छवि का पारदर्शी रंग।

**वापसी:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

छवि की पारदर्शी रंग को प्राप्त करता या सेट करता है।

मान: छवि का पारदर्शी रंग।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है।

**वापसी:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

निर्यातित दस्तावेज़ में इंक वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने-योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें boolean .

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

डिफ़ॉल्ट है **false** .

**वापसी:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें boolean .

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

डिफ़ॉल्ट है **false** .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |