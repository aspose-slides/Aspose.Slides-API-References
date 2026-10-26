---
title: Presentation
second_title: Aspose.Slides for Java API संदर्भ
description: Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/presentation/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

एक Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // एक Presentation ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड प्राप्त करें
>      ISlide slide = pres.getSlides().get_Item(0);
>      // लाइन प्रकार का ऑटोशेप जोड़ें
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // प्रस्तुति फ़ाइल सहेजें।
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Presentation में कोई भी समर्थित फ़ाइल लोड करें, जैसे ppt, pptx, odp आदि।
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // प्रस्तुति फ़ाइल सहेजें।
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## निर्माताओं

| निर्माता | विवरण |
| --- | --- |
| [Presentation()](#Presentation--) | यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है। |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है। |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के लिए प्राथमिक तंत्र है। |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के लिए प्राथमिक तंत्र है। |
| [Presentation(String file)](#Presentation-java.lang.String-) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है। |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | तारीख और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को बदलता है। |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | तारीख और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को बदलता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | वास्तविक HeaderFooter प्रबंधक लौटाता है। |
| [getProtectionManager()](#getProtectionManager--) | इस प्रस्तुति के अनुमतियों के प्रबंधक को प्राप्त करता है। |
| [getSlides()](#getSlides--) | प्रस्तुति में परिभाषित सभी स्लाइडों की सूची लौटाता है। |
| [getSections()](#getSections--) | प्रस्तुति में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। |
| [getSlideSize()](#getSlideSize--) | स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getNotesSize()](#getNotesSize--) | नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | प्रस्तुति में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। |
| [getMasters()](#getMasters--) | प्रस्तुति में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | नोट्स मास्टर प्रबंधक लौटाता है। |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | हैंडआउट मास्टर प्रबंधक लौटाता है। |
| [getFontsManager()](#getFontsManager--) | फ़ॉन्ट प्रबंधक लौटाता है। |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | आकारों के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। |
| [getCommentAuthors()](#getCommentAuthors--) | टिप्पणी लेखकों का संग्रह लौटाता है। |
| [getDocumentProperties()](#getDocumentProperties--) | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। |
| [getImages()](#getImages--) | प्रस्तुति में सभी छवियों का संग्रह लौटाता है। |
| [getAudios()](#getAudios--) | प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। |
| [getVideos()](#getVideos--) | प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। |
| [getSlideShowSettings()](#getSlideShowSettings--) | प्रस्तुति के स्लाइडशो सेटिंग्स लौटाता है। |
| [getDigitalSignatures()](#getDigitalSignatures--) | प्रस्तुति पर हस्ताक्षर करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। |
| [getCustomData()](#getCustomData--) | प्रस्तुति का कस्टम डेटा लौटाता है। |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | प्रस्तुति में सभी कस्टम डेटा भाग लौटाता है। |
| [getVbaProject()](#getVbaProject--) | प्रस्तुति मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता या सेट करता है। |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | प्रस्तुति मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता या सेट करता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | सभी प्रस्तुति स्लाइडों (मास्टर, लेआउट, नोट्स स्लाइड नहीं) में मौजूद सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। |
| [getViewProperties()](#getViewProperties--) | प्रस्तुति-व्यापी दृश्य गुण प्राप्त करता है। |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | प्रस्तुति में पहला स्लाइड नंबर दर्शाता है |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | प्रस्तुति में पहला स्लाइड नंबर दर्शाता है |
| [getSensitivityLabels()](#getSensitivityLabels--) | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबलों का संग्रह लौटाता है। |
| [getSlideById(long id)](#getSlideById-long-) | Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है। |
| [getSourceFormat()](#getSourceFormat--) | प्रस्तुति किस फ़ॉर्मेट से लोड किया गया था, इसकी जानकारी लौटाता है। |
| [getMasterTheme()](#getMasterTheme--) | मास्टर थीम लौटाता है। |
| [save(String fname, int format)](#save-java.lang.String-int-) | निर्दिष्ट फ़ॉर्मेट के साथ फ़ाइल में प्रस्तुति की सभी स्लाइडें सहेजता है। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में प्रस्तुति की सभी स्लाइडें सहेजता है। |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ फ़ाइल में प्रस्तुति की सभी स्लाइडें सहेजता है। |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रीम में प्रस्तुति की सभी स्लाइडें सहेजता है। |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | XAML मार्कअप दर्शाने वाली फ़ाइलों के सेट में प्रस्तुति की सभी स्लाइडें सहेजता है। |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | प्रस्तुति की सभी स्लाइडों के लिए Image ऑब्जेक्ट लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट लौटाता है। |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | कस्टम स्केलिंग के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट लौटाता है। |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | निर्दिष्ट आकार के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट लौटाता है। |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | निर्दिष्ट स्लाइडों को पृष्ठ संख्याएँ रखकर निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट स्लाइडों को पृष्ठ संख्याएँ रखकर निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | निर्दिष्ट स्लाइडों को पृष्ठ संख्याएँ रखकर निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट स्लाइडों को पृष्ठ संख्याएँ रखकर निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी पैराग्राफ़ों में समान फॉर्मेट वाले रन को सभी स्वीकृत आकारों में जोड़ता है। |
| [dispose()](#dispose--) | इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [getPresentation()](#getPresentation--) | टेक्स्ट का पैरेंट प्रस्तुति लौटाता है। |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट टेक्स्ट के सभी उदाहरणों को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |
### Presentation() {#Presentation--}
```
public Presentation()
```

यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है। निर्मित प्रस्तुति में एक खाली स्लाइड होती है।

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है। निर्मित प्रस्तुति में एक खाली स्लाइड होती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के लिए प्राथमिक तंत्र है।

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम। |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के लिए प्राथमिक तंत्र है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है।

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | इनपुट फ़ाइल। |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | इनपुट फ़ाइल। |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

तारीख और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को बदलता है। इस Presentation ऑब्जेक्ट के निर्माण का समय डिफ़ॉल्ट है। पढ़ें/लिखें java.util.Date।

**रिटर्न:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

तारीख और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को बदलता है। इस Presentation ऑब्जेक्ट के निर्माण का समय डिफ़ॉल्ट है। पढ़ें/लिखें java.util.Date।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

वास्तविक HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)।

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible is used for indicating that a slide footer placeholder is not present.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility is used for making a slide footer placeholder visible.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible is used for indicating that a slide page number placeholder is not present.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility is used for making a slide page number placeholder visible.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible is used for indicating that a slide date-time placeholder is not present.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility is used for making a slide date-time placeholder visible.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText is used for setting text to slide footer placeholder.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText is used for setting text to slide date-time placeholder.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility is used for making a master slide and all child footer placeholders visible.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility is used for making a master slide and all child page number placeholders visible.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility is used for making a master slide and all child date-time placeholders visible.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText is used for setting text to master slide and all child footer placeholders.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText is used for setting text to master slide and all child date-time placeholders.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

इस प्रस्तुति के अनुमतियों के प्रबंधक को प्राप्त करता है। केवल-पढ़ने योग्य [IProtectionManager](../../com.aspose.slides/iprotectionmanager)।

**रिटर्न:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

प्रस्तुति में परिभाषित सभी स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [ISlideCollection](../../com.aspose.slides/islidecollection)।

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the first ISlide to Blue
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Set the background with Image
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Set the picture
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Add image to presentation's images collection
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Write the presentation to disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instantiate Presentation class that represents a presentation file
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Set the transition time of 3 seconds
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Set the transition time of 5 seconds
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Apply zoom type transition on slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Set the transition time of 7 seconds
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

प्रस्तुति में सभी स्लाइड सेक्शन की सूची लौटाता है। केवल-पढ़ने योग्य [ISectionCollection](../../com.aspose.slides/isectioncollection)।

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 will be ended at newSlide2 and after it section2 will start
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ISlideSize](../../com.aspose.slides/islidesize)।

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Set the slide size of generated presentations to that of source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize is used for set slide size with scale content to ensure fit
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize is used for set slide size with maximize size of content
>          // Save Presentation to disk
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 paper size
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [INotesSize](../../com.aspose.slides/inotessize)।

**रिटर्न:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

प्रस्तुति में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)।

--------------------

आप वैकल्पिक API का उपयोग करके IMasterSlide.LayoutSlides प्रॉपर्टी के द्वारा लेआउट स्लाइडों को जोड़/डाल/हटा/क्लोन कर सकते हैं।

**रिटर्न:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

प्रस्तुति में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)।

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

नोट्स मास्टर प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)।

**रिटर्न:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

हैंडआउट मास्टर प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)।

**रिटर्न:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

फ़ॉन्ट प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IFontsManager](../../com.aspose.slides/ifontsmanager)।

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Load presentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Load source font to be replaced
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Save the presentation
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

आकारों के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

टिप्पणी लेखकों का संग्रह लौटाता है। केवल-पढ़ने योग्य [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)।

**रिटर्न:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। केवल-पढ़ने योग्य [IDocumentProperties](../../com.aspose.slides/idocumentproperties)।

**रिटर्न:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

प्रस्तुति में सभी छवियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IImageCollection](../../com.aspose.slides/iimagecollection)।

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // नई प्रस्तुति बनाएं जिसमें छवि जोड़ी जाएगी।
>  Presentation pres = new Presentation();
>  try
>  {
>      // मान लेते हैं कि हमारे पास बड़ी छवि फ़ाइल है जिसे हम प्रस्तुति में शामिल करना चाहते हैं
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // आइए छवि को प्रस्तुति में जोड़ें - हम KeepLocked व्यवहार चुनते हैं क्योंकि हम
>          // NOT ऐसी "largeImage.png" फ़ाइल तक पहुंच नहीं चाहते।
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // प्रस्तुति को सहेजता है। जबकि बड़ी प्रस्तुति आउटपुट होती है, मेमोरी खपत
>          // pres ऑब्जेक्ट के जीवनचक्र के दौरान कम रहती है
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // प्रस्तुति में छवि जोड़ें
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // पहले जोड़ी गई छवि के आधार पर स्लाइड 1 पर चित्र फ्रेम बनाता है
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAudioCollection](../../com.aspose.slides/iaudiocollection)।

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल पढ़ने योग्य [IVideoCollection](../../com.aspose.slides/ivideocollection).

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

प्रस्तुति के स्लाइड शो सेटिंग्स लौटाता है।

**वापसी:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

प्रस्तुति को साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल पढ़ने योग्य [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

**वापसी:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

प्रस्तुति का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata)।

**वापसी:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

प्रस्तुति में सभी कस्टम डेटा पार्ट्स लौटाता है। केवल पढ़ने योग्य ICustomXmlPart[]।

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // सभी कस्टम XML पार्ट्स पर इटररेट करें
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

प्रस्तुति मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IVbaProject](../../com.aspose.slides/ivbaproject)।

**वापसी:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

प्रस्तुति मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IVbaProject](../../com.aspose.slides/ivbaproject)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

सभी प्रस्तुति स्लाइड्स (मास्टर, लेआउट, नोट्स स्लाइड्स में नहीं) में मौजूद सभी हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)।

**वापसी:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

प्रस्तुति-व्यापी दृश्य गुणों को प्राप्त करता है। केवल पढ़ने योग्य [IViewProperties](../../com.aspose.slides/iviewproperties)।

**वापसी:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

प्रस्तुति में पहली स्लाइड संख्या को दर्शाता है

**वापसी:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

प्रस्तुति में पहली स्लाइड संख्या को दर्शाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल पढ़ने योग्य [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Print the applied labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Add the new label
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Get the sensitivity label Id from the policy
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Get the Azure AD site identifier from the policy
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Id द्वारा एक Slide, MasterSlide या LayoutSlide लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | long | स्लाइड का Id। |
**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

प्रस्तुति किस फॉर्मेट से लोड हुई थी, इस बारे में जानकारी लौटाता है। केवल पढ़ने योग्य [SourceFormat](../../com.aspose.slides/sourceformat)।

**वापसी:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

मास्टर थीम लौटाता है। केवल पढ़ने योग्य [IMasterTheme](../../com.aspose.slides/imastertheme)।

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // एक प्रस्तुति ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फॉर्मेट वाली फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाई गई फ़ाइल का पथ। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फॉर्मेट में एक स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फॉर्मेट और अतिरिक्त फॉर्मेट विकल्पों के साथ फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाई गई फ़ाइल का पथ। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फॉर्मेट विकल्प। |
### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फॉर्मेट और अतिरिक्त फॉर्मेट विकल्पों के साथ स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फॉर्मेट विकल्प। |
### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML फॉर्मेट विकल्प। |
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

प्रस्तुति की सभी स्लाइड्स के लिए Image objects लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
**वापसी:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options)
```

निर्देशित स्लाइड्स के लिए Thumbnail Image objects लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
**वापसी:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

प्रस्तुति की सभी स्लाइड्स के लिए कस्टम स्केलिंग के साथ Thumbnail Image objects लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| scaleX | float | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | float | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
**वापसी:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

निर्देशित स्लाइड्स के लिए कस्टम स्केलिंग के साथ Thumbnail Image objects लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| scaleX | float | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | float | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
**वापसी:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

निर्दिष्ट आकार के साथ प्रस्तुति की सभी स्लाइड्स के लिए Thumbnail Image objects लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| imageSize | java.awt.Dimension | बनाने के लिए छवि का आकार। |
**वापसी:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

निर्देशित स्लाइड्स के लिए निर्दिष्ट आकार के साथ Thumbnail Image objects लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| imageSize | java.awt.Dimension | बनाने के लिए छवि का आकार। |
**वापसी:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

प्रस्तुति की निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फॉर्मेट वाली फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाई गई फ़ाइल का पथ। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

प्रस्तुति की निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फॉर्मेट और अतिरिक्त फॉर्मेट विकल्पों के साथ फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाई गई फ़ाइल का पथ। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फॉर्मेट विकल्प। |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फॉर्मेट में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फॉर्मेट और अतिरिक्त फॉर्मेट विकल्पों के साथ स्ट्रीम में सहेजता है।

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | int | निर्यातित डेटा का फॉर्मेट। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त फॉर्मेट विकल्प। |
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

सभी स्लाइड्स में सभी स्वीकार्य आकारों में सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### dispose() {#dispose--}
```
public final void dispose()
```

इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है।

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

टेक्स्ट का पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

उदाहरण टेक्स्ट की सभी मेलों को निर्दिष्ट रंग के साथ हाइलाइट करता है।

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

उदाहरण टेक्स्ट की सभी मेलों को निर्दिष्ट रंग के साथ हाइलाइट करता है।

> ```
> PowerPoint प्रस्तुति में टेक्स्ट हाइलाइट करने का कोड उदाहरण।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' घटनाओं को हाइलाइट कर रहा है
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

रेगुलर एक्सप्रेशन की सभी मेलों को निर्दिष्ट रंग के साथ हाइलाइट करता है।

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10 अक्षर या अधिक वाले सभी शब्दों को हाइलाइट कर रहा है
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिए स्ट्रिंग्स प्राप्त करने हेतु रेगुलर एक्सप्रेशन java.util.regex.Pattern। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)।
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट पाठ के सभी उदाहरणों को दूसरे निर्दिष्ट पाठ से बदलता है।

--------------------

> ```
> निम्न नमूना कोड दिखाता है कि कैसे एक निर्दिष्ट स्ट्रिंग को दूसरी निर्दिष्ट स्ट्रिंग से बदलें।
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग 'the' घटनाओं को '***' से बदलें
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने वाला स्ट्रिंग। |
| newText | java.lang.String | oldText के सभी उदाहरणों को बदलने वाला स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | पाठ खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // सभी शब्दों को 10 या अधिक अक्षरों वाले को '***' से बदलें
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिए स्ट्रिंग प्राप्त करने हेतु नियमित अभिव्यक्ति java.util.regex.Pattern। |
| newText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |