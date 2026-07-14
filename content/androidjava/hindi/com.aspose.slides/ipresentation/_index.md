---
title: IPresentation
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रेजेंटेशन दस्तावेज़
type: docs
url: /hi/com.aspose.slides/ipresentation/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable  
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentation document
## विधियां

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | दिनांक-समय फ़ील्ड्स की सामग्री के स्थान पर प्रतिस्थापित करने के लिए दिनांक और समय को लौटाता है या सेट करता है। |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | दिनांक-समय फ़ील्ड्स की सामग्री के स्थान पर प्रतिस्थापित करने के लिए दिनांक और समय को लौटाता है या सेट करता है। |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | प्रेजेंटेशन का HeaderFooter प्रबंधक लौटाता है। |
| [getProtectionManager()](#getProtectionManager--) | इस प्रेजेंटेशन के अनुमतियों का प्रबंधक प्राप्त करता है। |
| [getSlides()](#getSlides--) | प्रेजेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है। |
| [getSections()](#getSections--) | प्रेजेंटेशन में परिभाषित सभी स्लाइड सेक्शन्स की सूची लौटाता है। |
| [getSlideSize()](#getSlideSize--) | स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getNotesSize()](#getNotesSize--) | नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | प्रेजेंटेशन में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। |
| [getMasters()](#getMasters--) | प्रेजेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | नोट्स मास्टर प्रबंधक लौटाता है। |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | हैंडआउट मास्टर प्रबंधक लौटाता है। |
| [getFontsManager()](#getFontsManager--) | फ़ॉन्ट्स प्रबंधक लौटाता है। |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। |
| [getCommentAuthors()](#getCommentAuthors--) | टिप्पणियों के लेखकों का संग्रह लौटाता है। |
| [getDocumentProperties()](#getDocumentProperties--) | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। |
| [getImages()](#getImages--) | प्रेजेंटेशन में सभी छवियों का संग्रह लौटाता है। |
| [getAudios()](#getAudios--) | प्रेजेंटेशन में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। |
| [getVideos()](#getVideos--) | प्रेजेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। |
| [getCustomData()](#getCustomData--) | प्रेजेंटेशन का कस्टम डेटा लौटाता है। |
| [getVbaProject()](#getVbaProject--) | प्रेजेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट प्राप्त करता है। |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | प्रेजेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट प्राप्त करता है। |
| [getSourceFormat()](#getSourceFormat--) | प्रेजेंटेशन किस फ़ॉर्मेट से लोड किया गया था, इसकी जानकारी लौटाता है। |
| [getMasterTheme()](#getMasterTheme--) | प्रेजेंटेशन की मास्टर थीम लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | सभी प्रेजेंटेशन स्लाइड्स में मौजूद सभी हाइपरलिंक्स तक आसान पहुँच प्रदान करता है (मास्टर, लेआउट, नोट्स स्लाइड्स में नहीं)। |
| [getViewProperties()](#getViewProperties--) | प्रेजेंटेशन-व्यापी व्यू प्रॉपर्टीज़ प्राप्त करता है। |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | प्रेजेंटेशन में पहला स्लाइड नंबर दर्शाता है। |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | प्रेजेंटेशन में पहला स्लाइड नंबर दर्शाता है। |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | प्रेजेंटेशन में सभी कस्टम डेटा भागों को लौटाता है। |
| [getDigitalSignatures()](#getDigitalSignatures--) | प्रेजेंटेशन पर साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। |
| [getSensitivityLabels()](#getSensitivityLabels--) | प्रेजेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। |
| [save(String fname, int format)](#save-java.lang.String-int-) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है। |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेजेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेजेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है। |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को फ़ाइल में सहेजता है। |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को स्ट्रीम में सहेजता है। |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में प्रेजेंटेशन की सभी स्लाइड्स को सहेजता है। |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | कस्टम स्केलिंग के साथ प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | निर्दिष्ट आकार के साथ प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [getSlideById(long id)](#getSlideById-long-) | Id द्वारा स्लाइड, मास्टरस्लाइड या लेआउटस्लाइड लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी स्लाइडों में सभी स्वीकार्य शेप्स के सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है। |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है। |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाईलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है। |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

दिनांक-समय फ़ील्ड्स की सामग्री के स्थान पर प्रतिस्थापित करने के लिए दिनांक और समय को लौटाता है या सेट करता है। यह प्रेजेंटेशन ऑब्जेक्ट के निर्माण का समय है (डिफ़ॉल्ट)। पढ़ें/लिखें java.util.Date.

**Returns:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

दिनांक-समय फ़ील्ड्स की सामग्री के स्थान पर प्रतिस्थापित करने के लिए दिनांक और समय को लौटाता है या सेट करता है। यह प्रेजेंटेशन ऑब्जेक्ट के निर्माण का समय है (डिफ़ॉल्ट)। पढ़ें/लिखें java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

प्रेजेंटेशन का HeaderFooter प्रबंधक लौटाता है। केवल पढ़ने योग्य [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Returns:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

इस प्रेजेंटेशन के अनुमतियों का प्रबंधक प्राप्त करता है। केवल पढ़ने योग्य [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returns:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

प्रेजेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है। केवल पढ़ने योग्य [ISlideCollection](../../com.aspose.slides/islidecollection).

**Returns:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

प्रेजेंटेशन में परिभाषित सभी स्लाइड सेक्शन्स की सूची लौटाता है। केवल पढ़ने योग्य [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Returns:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ISlideSize](../../com.aspose.slides/islidesize).

**Returns:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [INotesSize](../../com.aspose.slides/inotessize).

**Returns:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

प्रेजेंटेशन में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। केवल पढ़ने योग्य [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

आप IMasterSlide.LayoutSlides प्रॉपर्टी का उपयोग करके लेआउट स्लाइड्स को जोड़ने/घटाने/क्लोन करने के वैकल्पिक API तक पहुँच सकते हैं।

**Returns:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

प्रेजेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल पढ़ने योग्य [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Returns:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

नोट्स मास्टर प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returns:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

हैंडआउट मास्टर प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returns:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

फ़ॉन्ट्स प्रबंधक लौटाता है। केवल पढ़ने योग्य [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Returns:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

टिप्पणियों के लेखकों का संग्रह लौटाता है। केवल पढ़ने योग्य [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returns:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। केवल पढ़ने योग्य [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

प्रेजेंटेशन में सभी छवियों का संग्रह लौटाता है। केवल पढ़ने योग्य [IImageCollection](../../com.aspose.slides/iimagecollection).

**Returns:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

प्रेजेंटेशन में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल पढ़ने योग्य [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Returns:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

प्रेजेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल पढ़ने योग्य [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Returns:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

प्रेजेंटेशन का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

प्रेजेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट प्राप्त करता है। पढ़ें/लिखें [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

प्रेजेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट प्राप्त करता है। पढ़ें/लिखें [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

प्रेजेंटेशन किस फ़ॉर्मेट से लोड किया गया था, इसकी जानकारी लौटाता है। केवल पढ़ने योग्य [SourceFormat](../../com.aspose.slides/sourceformat).

**Returns:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

प्रेजेंटेशन की मास्टर थीम लौटाता है। केवल पढ़ने योग्य [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returns:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

सभी प्रेजेंटेशन स्लाइड्स में मौजूद सभी हाइपरलिंक्स तक आसान पहुँच प्रदान करता है (मास्टर, लेआउट, नोट्स स्लाइड्स में नहीं)। केवल पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

प्रेजेंटेशन-व्यापी व्यू प्रॉपर्टीज़ प्राप्त करता है। केवल पढ़ने योग्य [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returns:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

प्रेजेंटेशन में पहला स्लाइड नंबर दर्शाता है। पढ़ें/लिखें int.

**Returns:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

प्रेजेंटेशन में पहला स्लाइड नंबर दर्शाता है। पढ़ें/लिखें int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

प्रेजेंटेशन में सभी कस्टम डेटा भागों को लौटाता है। केवल पढ़ने योग्य ICustomXmlPart[].

**Returns:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

हस्ताक्षरों का संग्रह लौटाता है जो प्रेजेंटेशन पर साइन करने के लिए उपयोग किए गए हैं। केवल पढ़ने योग्य [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Returns:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

प्रेजेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल पढ़ने योग्य [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // लगाए गए लेबल प्रिंट करें
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // नया लेबल जोड़ें
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // नीति से सेंसिटिविटी लेबल Id प्राप्त करें
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // नीति से Azure AD साइट आइडेंटिफायर प्राप्त करें
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | बनायी गयी फ़ाइल का पथ। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेजेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | बनायी गयी फ़ाइल का पथ। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेजेंटेशन की सभी स्लाइड्स को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को फ़ाइल में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | बनायी गयी फ़ाइल का पथ। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को फ़ाइल में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | बनायी गयी फ़ाइल का पथ। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |
| format | int | निर्यात डेटा का फ़ॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में प्रेजेंटेशन की सभी स्लाइड्स को सहेजता है।

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


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML फ़ॉर्मेट विकल्प। |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

निर्दिष्ट स्लाइड्स के लिए थंबनेल IImage ऑब्जेक्ट्स लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

कस्टम स्केलिंग के साथ प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| scaleX | float | X-अक्ष दिशा में थंबनेल को स्केल करने का मान। |
| scaleY | float | Y-अक्ष दिशा में थंबनेल को स्केल करने का मान। |

**Returns:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |
| scaleX | float | X-अक्ष दिशा में थंबनेल को स्केल करने का मान। |
| scaleY | float | Y-अक्ष दिशा में थंबनेल को स्केल करने का मान। |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

निर्दिष्ट आकार के साथ प्रेजेंटेशन की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| imageSize | [Size](../../com.aspose.slides.android/size) | बनाय जाने वाले इमेज का आकार। |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| slides | int[] | स्लाइड पोजीशन की ऐरे, 1-से शुरू। |
| imageSize | [Size](../../com.aspose.slides.android/size) | बनाय जाने वाले इमेज का आकार। |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Id द्वारा स्लाइड, मास्टरस्लाइड या लेआउटस्लाइड लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | स्लाइड की Id। |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

सभी स्लाइडों में सभी स्वीकार्य शेप्स के सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है।

--------------------

> ```
> निम्न कोड उदाहरण दिखाता है कि PowerPoint प्रस्तुति में टेक्स्ट को कैसे हाईलाइट किया जाए।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // सभी अलग-अलग 'the' घटनाओं को हाईलाइट कर रहा है
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | हाईलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.lang.Integer | टेक्स्ट को हाईलाइट करने का रंग। |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // सभी अलग-अलग 'the' घटनाओं को हाईलाइट कर रहा है
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | हाईलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.lang.Integer | टेक्स्ट को हाईलाइट करने का रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट सर्च विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाईलाइट करता है।

--------------------

> ```
> निम्न कोड उदाहरण दिखाता है कि नियमित अभिव्यक्ति का उपयोग करके PowerPoint प्रस्तुति में टेक्स्ट को कैसे हाईलाइट किया जाए।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // सभी अलग-अलग 'the' घटनाओं को हाईलाइट कर रहा है
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिये नियमित अभिव्यक्ति। |
| highlightColor | java.lang.Integer | टेक्स्ट को हाईलाइट करने का रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिये कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है।

--------------------

> ```
> निम्न नमूना कोड दिखाता है कि एक निर्दिष्ट स्ट्रिंग को दूसरी निर्दिष्ट स्ट्रिंग से कैसे बदलें।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' घटनाओं को '***' से बदलें
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | बदलने वाला स्ट्रिंग। |
| newText | java.lang.String | सभी घटनाओं को बदलने वाला स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट सर्च विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिये कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> निम्न कोड उदाहरण दिखाता है कि नियमित अभिव्यक्ति का उपयोग करके निर्दिष्ट स्ट्रिंग के साथ टेक्स्ट को कैसे बदलें।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' घटनाओं को '***' से बदलें
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिये नियमित अभिव्यक्ति। |
| newText | java.lang.String | सभी घटनाओं को बदलने वाला स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिये कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |