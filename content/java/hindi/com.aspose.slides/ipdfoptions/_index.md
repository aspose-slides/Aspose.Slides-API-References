---
title: IPdfOptions
second_title: Aspose.Slides के लिए Java API संदर्भ
description: ऐसे विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रेजेंटेशन को Pdf फॉर्मेट में कैसे सहेजा जाए।
type: docs
url: /hi/com.aspose.slides/ipdfoptions/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को Pdf प्रारूप में कैसे सहेजा जाए।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [setTextCompression(int value)](#setTextCompression-int-) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए या नहीं। |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए या नहीं। |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII अक्षरों 32-127 के लिए True Type फ़ॉन्ट को एम्बेड करने के लिए true। |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII अक्षरों 32-127 के लिए True Type फ़ॉन्ट को एम्बेड करने के लिए true। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | यह दर्शाता है कि जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है तो पाठ को बिटमैप के रूप में रास्टराइज़ कर PDF में सहेजा जाना चाहिए या नहीं। |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | यह दर्शाता है कि जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है तो पाठ को बिटमैप के रूप में रास्टराइज़ कर PDF में सहेजा जाना चाहिए या नहीं। |
| [getJpegQuality()](#getJpegQuality--) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता या सेट करता है। |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता या सेट करता है। |
| [getCompliance()](#getCompliance--) | उत्पन्न PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। |
| [setCompliance(int value)](#setCompliance-int-) | उत्पन्न PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। |
| [getPassword()](#getPassword--) | PDF दस्तावेज़ को सुरक्षित रखने के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF दस्तावेज़ को सुरक्षित रखने के लिए उपयोगकर्ता पासवर्ड सेट करना। |
| [getAccessPermissions()](#getAccessPermissions--) | फ़्लैग्स का एक सेट शामिल करता है जो निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर कौन सी अभिगम अनुमतियाँ प्रदान किए जाने चाहिए। |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | फ़्लैग्स का एक सेट शामिल करता है जो निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर कौन सी अभिगम अनुमतियाँ प्रदान किए जाने चाहिए। |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | प्रस्तुति में उपयोग किए गए सभी मेटाफाइल को PNG छवियों में बदलने के लिए true। |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | प्रस्तुति में उपयोग किए गए सभी मेटाफाइल को PNG छवियों में बदलने केके लिए true। |
| [getSufficientResolution()](#getSufficientResolution--) | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता या सेट करता है। |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता या सेट करता है। |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाने के लिए true। |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाने के लिए true। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं उसे प्राप्त या सेट करता है। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं उसे प्राप्त या सेट करता है। |
| [getImageTransparentColor()](#getImageTransparentColor--) | छवि के पारदर्शी रंग को प्राप्त या सेट करता है। |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | छवि के पारदर्शी रंग को प्राप्त या सेट करता है। |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स के स्वरूप को नियंत्रित करने के विकल्प प्रदान करता है। |
| [getIncludeOleData()](#getIncludeOleData--) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

डिफ़ॉल्ट है [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**रिटर्न:**
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

यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए या नहीं। यदि true सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा रहेगा।

--------------------

सबसे अच्छा इमेज संपीड़न अनुपात चयन महँगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से false है।

--------------------

डिफ़ॉल्ट है false.

**रिटर्न:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए या नहीं। यदि true सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीढ़न एल्गोरिद्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा रहेगा।

--------------------

सबसे अच्छा इमेज संपीड़न अनुपात चयन महँगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से false है।

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

ASCII वर्ण 32-127 के लिए True Type फ़ॉन्ट को एम्बेड करने के लिए true। 127 से बड़े कोड वाले फ़ॉन्ट हमेशा एम्बेड किए जाते हैं। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**.

**रिटर्न:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

ASCII वर्ण 32-127 के लिए True Type फ़ॉन्ट को एम्बेड करने के लिए true। 127 से बड़े कोड वाले फ़ॉन्ट हमेशा एम्बेड किए जाते हैं। पढ़ें/लिखें boolean.

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

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। डिफ़ॉल्ट है false.

**रिटर्न:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। डिफ़ॉल्ट है false.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। पढ़ें/लिखें String[].

**रिटर्न:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। पढ़ें/लिखें String[].

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**रिटर्न:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। पढ़ें/लिखें boolean.

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

यह दर्शाता है कि जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है तो पाठ को बिटमैप के रूप में रास्टराइज़ कर PDF में सहेजा जाना चाहिए या नहीं। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में पाठ की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**रिटर्न:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

यह दर्शाता है कि जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है तो पाठ को बिटमैप के रूप में रास्टराइज़ कर PDF में सहेजा जाना चाहिए या नहीं। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में पाठ की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें boolean.

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

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता या सेट करता है। पढ़ें/लिखें byte.

--------------------

केवल तब प्रभाव डालता है जब दस्तावेज़ में JPEG छवियाँ हों।

इस प्रॉपर्टी का उपयोग तब किया जाता है जब PDF प्रारूप में सहेजते समय छवियों की गुणवत्ता प्राप्त या सेट करनी हो। मान 0 से 100 तक हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **100** है।

**रिटर्न:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता या सेट करता है। पढ़ें/लिखें byte.

--------------------

केवल तब प्रभाव डालता है जब दस्तावेज़ में JPEG छवियाँ हों।

इस प्रॉपर्टी का उपयोग तब किया जाता है जब PDF प्रारूप में सहेजते समय छवियों की गुणवत्ता प्राप्त या सेट करनी हो। मान 0 से 100 तक हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

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

**रिटर्न:**
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

PDF दस्तावेज़ को सुरक्षित रखने के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF दस्तावेज़ को सुरक्षित रखने के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

फ़्लैग्स का एक सेट शामिल करता है जो निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर कौन सी अभिगम अनुमतियाँ प्रदान किए जाने चाहिए। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

फ़्लैग्स का एक सेट शामिल करता है जो निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर कौन सी अभिगम अनुमतियाँ प्रदान किए जाने चाहिए। देखें [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

प्रस्तुति में उपयोग किए गए सभी मेटाफाइल को PNG छवियों में बदलने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**। Pdf दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों दोनों को शामिल कर सकता है। यदि SaveMetafilesAsPng true सेट किया जाता है तो स्रोत Metafile छवि को Png प्रारूप में बदलकर रास्टर छवि के रूप में Pdf में सहेजा जाता है। यदि SaveMetafilesAsPng false सेट किया जाता है तो स्रोत Metafile को Pdf वेक्टर ग्राफ़िक्स में बदला जाता है। प्रत्येक दृष्टिकोण के अपने लाभ और हानि हैं। उदाहरण के लिए, यदि Metafile को PNG में बदला जाता है, तो परिणामस्वरूप दस्तावेज़ के स्केलेशन के दौरान कुछ गुणवत्ता हानि हो सकती है। यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में बदला जाता है, तो Pdf व्यूअर टूल में प्रदर्शन समस्याएँ हो सकती हैं।

**रिटर्न:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

प्रस्तुति में उपयोग किए गए सभी मेटाफाइल को PNG छवियों में बदलने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **true**। Pdf दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों दोनों को शामिल कर सकता है। यदि SaveMetafilesAsPng true सेट किया जाता है तो स्रोत Metafile छवि को Png प्रारूप में बदलकर रास्टर छवि के रूप में Pdf में सहेजा जाता है। यदि SaveMetafilesAsPng false सेट किया जाता है तो स्रोत Metafile को Pdf वेक्टर ग्राफ़िक्स में बदला जाता है। प्रत्येक दृष्टिकोण के अपने लाभ और हानि हैं। उदाहरण के लिए, यदि Metafile को PNG में बदला जाता है, तो परिणामस्वरूप दस्तावेज़ के स्केलेशन के दौरान कुछ गुणवत्ता हानि हो सकती है। यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में बदला जाता है, तो Pdf व्यूअर टूल में प्रदर्शन समस्याएँ हो सकती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता या सेट करता है। पढ़ें/लिखें float.

मान: इस पैरामीटर का प्रभाव कुछ कारकों पर निर्भर करता है। एल्गोरिद्म प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के अनुसार सर्वश्रेष्ठ आउटपुट छवि आकार पाने की कोशिश करता है। समान प्रॉपर्टी मान समान परिणाम दे सकते हैं। दृश्य प्रभाव पाने के लिए 16 या 32 की स्टेप का उपयोग करने की सिफारिश की जाती है।

--------------------

प्रॉपर्टी फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करती है।

डिफ़ॉल्ट मान **96** है।

**रिटर्न:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता या सेट करता है। पढ़ें/लिखें float.

मान: इस पैरामीटर का प्रभाव कुछ कारकों पर निर्भर करता है। एल्गोरिद्म प्रॉपर्टी मान, स्रोत छवि आकार और छवि फ्रेम आकार के अनुसार सर्वश्रेष्ठ आउटपुट छवि आकार पाने की कोशिश करता है। समान प्रॉपर्टी मान समान परिणाम दे सकते हैं। दृश्य प्रभाव पाने के लिए 16 या 32 की स्टेप का उपयोग करने की सिफ़ारिश की जाती है।

--------------------

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

प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाने के लिए true। पढ़ें/लिखें boolean.

--------------------

डिफ़ॉल्ट है **false**.

**रिटर्न:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाने के लिए true। पढ़ें/लिखें boolean.

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

जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइड्स पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है।

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) तो स्लाइड्स पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है।

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
public abstract Color getImageTransparentColor()
```

छवि के पारदर्शी रंग को प्राप्त या सेट करता है।

मान: छवि का पारदर्शी रंग।

**रिटर्न:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

छवि के पारदर्शी रंग को प्राप्त या सेट करता है।

मान: छवि का पारदर्शी रंग।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

यदि true हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है।

**रिटर्न:**
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

निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स के स्वरूप को नियंत्रित करने के विकल्प प्रदान करता है। Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें  boolean .

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

डिफ़ॉल्ट है  **false** .

**रिटर्न:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें  boolean .

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

डिफ़ॉल्ट है  **false** .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |