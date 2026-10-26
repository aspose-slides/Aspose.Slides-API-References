---
title: IPresentation
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति दस्तावेज़
type: docs
url: /hi/com.aspose.slides/ipresentation/
---
**सभी लागू किए गए इंटरफ़ेस:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

प्रेज़ेंटेशन दस्तावेज़
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | डेटा और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | डेटा और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | प्रेज़ेंटेशन का HeaderFooter प्रबंधक लौटाता है। |
| [getProtectionManager()](#getProtectionManager--) | इस प्रेज़ेंटेशन के अनुमतियों के प्रबंधक को प्राप्त करता है। |
| [getSlides()](#getSlides--) | प्रेज़ेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है। |
| [getSections()](#getSections--) | प्रेज़ेंटेशन में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। |
| [getSlideSize()](#getSlideSize--) | स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getNotesSize()](#getNotesSize--) | नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | प्रेज़ेंटेशन में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। |
| [getMasters()](#getMasters--) | प्रेज़ेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | नोट्स मास्टर प्रबंधक लौटाता है। |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | हैंडआउट मास्टर प्रबंधक लौटाता है। |
| [getFontsManager()](#getFontsManager--) | फ़ॉन्ट्स प्रबंधक लौटाता है। |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। |
| [getCommentAuthors()](#getCommentAuthors--) | टिप्पणी लेखकों का संग्रह लौटाता है। |
| [getDocumentProperties()](#getDocumentProperties--) | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। |
| [getImages()](#getImages--) | प्रेज़ेंटेशन में सभी चित्रों का संग्रह लौटाता है। |
| [getAudios()](#getAudios--) | प्रेज़ेंटेशन में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। |
| [getVideos()](#getVideos--) | प्रेज़ेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। |
| [getCustomData()](#getCustomData--) | प्रेज़ेंटेशन का कस्टम डेटा लौटाता है। |
| [getVbaProject()](#getVbaProject--) | प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता है। |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता है। |
| [getSourceFormat()](#getSourceFormat--) | प्रेज़ेंटेशन किस फ़ॉर्मेट से लोड किया गया, इस बारे में जानकारी लौटाता है। |
| [getMasterTheme()](#getMasterTheme--) | प्रेज़ेंटेशन का मास्टर थीम लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | सभी प्रेज़ेंटेशन स्लाइड्स (मास्टर, लेआउट, नोट्स स्लाइड्स नहीं) में मौजूद सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। |
| [getViewProperties()](#getViewProperties--) | प्रेज़ेंटेशन-व्यापी दृश्य गुण प्राप्त करता है। |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | प्रेज़ेंटेशन में पहला स्लाइड नंबर दर्शाता है। |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | प्रेज़ेंटेशन में पहला स्लाइड नंबर दर्शाता है। |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | प्रेज़ेंटेशन में सभी कस्टम डेटा भाग लौटाता है। |
| [getDigitalSignatures()](#getDigitalSignatures--) | प्रेज़ेंटेशन को साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। |
| [getSensitivityLabels()](#getSensitivityLabels--) | प्रेज़ेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। |
| [save(String fname, int format)](#save-java.lang.String-int-) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेज़ेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | निर्दिष्ट फ़ॉर्मेट में प्रेज़ेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है। |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेज़ेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेज़ेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है। |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट के साथ फ़ाइल में सहेजता है। |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट के साथ फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | प्रेज़ेंटेशन की सभी स्लाइड्स को XAML मार्कअप के रूप में फ़ाइलों के सेट में सहेजता है। |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | निर्दिष्ट स्लाइड्स के लिए थंबनेल IImage ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | सभी स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | निर्दिष्ट स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | सभी स्लाइड्स के लिए निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | निर्दिष्ट स्लाइड्स के लिए निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getSlideById(long id)](#getSlideById-long-) | Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी स्लाइड्स में सभी स्वीकार्य शेप्स के सभी पैराग्राफ में समान फॉर्मेट वाले रन को जोड़ता है। |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है। |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है। |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाईलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है। |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

डेटा और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। डिफ़ॉल्ट रूप से इस Presentation ऑब्जेक्ट के निर्माण का समय। पढ़ें/लिखें java.util.Date.

**रिटर्न:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

डेटा और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। डिफ़ॉल्ट रूप से इस Presentation ऑब्जेक्ट के निर्माण का समय। पढ़ें/लिखें java.util.Date.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

प्रेज़ेंटेशन का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**रिटर्न:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

इस प्रेज़ेंटेशन के अनुमतियों के प्रबंधक को प्राप्त करता है। केवल-पढ़ने योग्य [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**रिटर्न:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

प्रेज़ेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [ISlideCollection](../../com.aspose.slides/islidecollection).

**रिटर्न:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

प्रेज़ेंटेशन में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। केवल-पढ़ने योग्य [ISectionCollection](../../com.aspose.slides/isectioncollection).

**रिटर्न:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ISlideSize](../../com.aspose.slides/islidesize).

**रिटर्न:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [INotesSize](../../com.aspose.slides/inotessize).

**रिटर्न:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

प्रेज़ेंटेशन में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

आप IMasterSlide.LayoutSlides प्रॉपर्टी का उपयोग करके लेआउट स्लाइड्स को जोड़ने/इंसर्ट करने/हटाने/क्लोन करने के वैकल्पिक API तक पहुंच सकते हैं।

**रिटर्न:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

प्रेज़ेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**रिटर्न:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

नोट्स मास्टर प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**रिटर्न:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

हैंडआउट मास्टर प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**रिटर्न:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

फ़ॉन्ट्स प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IFontsManager](../../com.aspose.slides/ifontsmanager).

**रिटर्न:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

टिप्पणी लेखकों का संग्रह लौटाता है। केवल-पढ़ने योग्य [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**रिटर्न:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। केवल-पढ़ने योग्य [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**रिटर्न:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

प्रेज़ेंटेशन में सभी चित्रों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IImageCollection](../../com.aspose.slides/iimagecollection).

**रिटर्न:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

प्रेज़ेंटेशन में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**रिटर्न:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

प्रेज़ेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IVideoCollection](../../com.aspose.slides/ivideocollection).

**रिटर्न:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

प्रेज़ेंटेशन का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata).

**रिटर्न:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता है। पढ़ें/लिखें [IVbaProject](../../com.aspose.slides/ivbaproject).

**रिटर्न:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता है। पढ़ें/लिखें [IVbaProject](../../com.aspose.slides/ivbaproject).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

प्रेज़ेंटेशन किस फ़ॉर्मेट से लोड किया गया, इस बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [SourceFormat](../../com.aspose.slides/sourceformat).

**रिटर्न:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

प्रेज़ेंटेशन का मास्टर थीम लौटाता है। केवल-पढ़ने योग्य [IMasterTheme](../../com.aspose.slides/imastertheme).

**रिटर्न:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

सभी प्रेज़ेंटेशन स्लाइड्स (मास्टर, लेआउट, नोट्स स्लाइड्स नहीं) में मौजूद सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**रिटर्न:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

प्रेज़ेंटेशन-व्यापी दृश्य गुण प्राप्त करता है। केवल-पढ़ने योग्य [IViewProperties](../../com.aspose.slides/iviewproperties).

**रिटर्न:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

प्रेज़ेंटेशन में पहला स्लाइड नंबर दर्शाता है। पढ़ें/लिखें int.

**रिटर्न:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

प्रेज़ेंटेशन में पहला स्लाइड नंबर दर्शाता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

प्रेज़ेंटेशन में सभी कस्टम डेटा भाग लौटाता है। केवल-पढ़ने योग्य ICustomXmlPart[].

**रिटर्न:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

प्रेज़ेंटेशन को साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

प्रेज़ेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // लागू लेबल प्रिंट करें
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // नया लेबल जोड़ें
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // नीति से संवेदनशीलता लेबल Id प्राप्त करें
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // नीति से Azure AD साइट पहचानकर्ता प्राप्त करें
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

निर्दिष्ट फ़ॉर्मेट के साथ प्रेज़ेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाए गए फ़ाइल का पथ। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

निर्दिष्ट फ़ॉर्मेट में प्रेज़ेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेज़ेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाए गए फ़ाइल का पथ। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```


एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में और अतिरिक्त विकल्पों के साथ एक स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```


निर्दिष्ट फ़ॉर्मेट के साथ प्रस्तुति की चयनित स्लाइड्स को फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fname | java.lang.String | निर्मित फ़ाइल का पथ। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```


निर्दिष्ट फ़ॉर्मेट के साथ प्रस्तुति की चयनित स्लाइड्स को फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fname | java.lang.String | निर्मित फ़ाइल का पथ। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```


निर्दिष्ट फ़ॉर्मेट में चयनित स्लाइड्स को एक स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


निर्दिष्ट फ़ॉर्मेट में चयनित स्लाइड्स को एक स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```


एक प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML फ़ॉर्मेट विकल्प। |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```


एक प्रस्तुति की सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |

**वापसी:**
com.aspose.slides.IImage[] - IImage ऑब्जेक्ट्स।

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```


निर्धारित स्लाइड्स के लिए थंबनेल IImage ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |

**वापसी:**
com.aspose.slides.IImage[] - IImage ऑब्जेक्ट्स।

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


सभी स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| scaleX | float | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | float | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

**वापसी:**
com.aspose.slides.IImage[] - Bitmap ऑब्जेक्ट्स।

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


निर्धारित स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |
| scaleX | float | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | float | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

**वापसी:**
com.aspose.slides.IImage[] - IImage ऑब्जेक्ट्स।

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


निर्दिष्ट आकार के साथ सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| imageSize | java.awt.Dimension | बनाए जाने वाली इमेज का आकार। |

**वापसी:**
com.aspose.slides.IImage[] - IImage ऑब्जेक्ट्स।

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


निर्दिष्ट आकार के साथ निर्धारित स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| slides | int[] | स्लाइड स्थितियों की ऐरे, 1 से शुरू। |
| imageSize | java.awt.Dimension | बनाए जाने वाली इमेज का आकार। |

**वापसी:**
com.aspose.slides.IImage[] - IImage ऑब्जेक्ट्स।

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```


Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| id | long | स्लाइड का Id। |

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide ऑब्जेक्ट।

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


सभी स्लाइड्स में सभी स्वीकार्य आकृतियों के सभी पैराग्राफ में समान फ़ॉर्मेटिंग वाले रन को मिलाता है।

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


नमूना टेक्स्ट के सभी मिलानों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> Presentation presentation = new Presentation("SomePresentation.pptx");
> try {
>     // सभी अलग-अलग 'the' उदाहरणों को हाइलाइट कर रहा है
>     presentation.highlightText("the", Color.MAGENTA);
>     presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
> } finally {
>     if (presentation != null) presentation.dispose();
> }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


नमूना टेक्स्ट के सभी मिलानों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // सभी अलग-अलग 'the' उदाहरणों को हाइलाइट कर रहा है
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> निम्नलिखित कोड नमूना दिखाता है कि नियमित अभिव्यक्ति का उपयोग करके PowerPoint प्रस्तुति में टेक्स्ट को कैसे हाइलाइट किया जाए।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // सभी अलग-अलग 'the' उदाहरणों को हाइलाइट कर रहा है
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिए स्ट्रिंग्स प्राप्त करने वाला नियमित अभिव्यक्ति java.util.regex.Pattern। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है।

--------------------

> ```
> नीचे दिया गया नमूना कोड दिखाता है कि एक निश्चित स्ट्रिंग को दूसरी निश्चित स्ट्रिंग से कैसे बदलें।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' उदाहरणों को '***' से बदलें
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| newText | java.lang.String | oldText की सभी घटनाओं को बदलने वाली स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> निम्नलिखित कोड नमूना दिखाता है कि नियमित अभिव्यक्ति का उपयोग करके निर्दिष्ट स्ट्रिंग के साथ टेक्स्ट को कैसे बदलें।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' उदाहरणों को '***' से बदलें
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिए स्ट्रिंग्स प्राप्त करने वाला नियमित अभिव्यक्ति java.util.regex.Pattern। |
| newText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |