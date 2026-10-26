---
title: Presentation
second_title: Aspose.Slides एण्ड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: Microsoft PowerPoint प्रस्तुति को दर्शाता है।
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
>  // एक Presentation ऑब्जेक्ट को इंस्टैंशिएट करें जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation();
>  try {
>      // पहला स्लाइड प्राप्त करें
>      ISlide slide = pres.getSlides().get_Item(0);
>      // लाइन प्रकार का एक ऑटॉशेप जोड़ें
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // प्रस्तुति फ़ाइल सहेजें।
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Presentation में कोई भी समर्थित फ़ाइल लोड करें, उदाहरण के लिए ppt, pptx, odp आदि।
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // प्रस्तुति फ़ाइल सहेजें।
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## कंस्ट्रक्टर्स

| निर्माता | विवरण |
| --- | --- |
| [Presentation()](#Presentation--) | यह कंस्ट्रक्टर शून्य से नई प्रस्तुति बनाता है। |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | यह कंस्ट्रक्टर शून्य से नई प्रस्तुति बनाता है। |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के मुख्य तंत्र के रूप में कार्य करता है। |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के मुख्य तंत्र के रूप में कार्य करता है। |
| [Presentation(String file)](#Presentation-java.lang.String-) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है। |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | दिनांक और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | दिनांक और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | वास्तविक HeaderFooter प्रबंधक लौटाता है। |
| [getProtectionManager()](#getProtectionManager--) | इस प्रस्तुति के लिए अनुमतियों के प्रबंधक को प्राप्त करता है। |
| [getSlides()](#getSlides--) | प्रस्तुति में परिभाषित सभी स्लाइडों की सूची लौटाता है। |
| [getSections()](#getSections--) | प्रस्तुति में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। |
| [getSlideSize()](#getSlideSize--) | स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getNotesSize()](#getNotesSize--) | नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | प्रस्तुति में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। |
| [getMasters()](#getMasters--) | प्रस्तुति में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | नोट्स मास्टर प्रबंधक लौटाता है। |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | हैंडआउट मास्टर प्रबंधक लौटाता है। |
| [getFontsManager()](#getFontsManager--) | फ़ॉन्ट्स प्रबंधक लौटाता है। |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | आकारों के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। |
| [getCommentAuthors()](#getCommentAuthors--) | टिप्पणियों के लेखकों का संग्रह लौटाता है। |
| [getDocumentProperties()](#getDocumentProperties--) | DocumentProperties ऑब्जेक्ट लौटाता है जो मानक और कस्टम दस्तावेज़ गुणों को शामिल करता है। |
| [getImages()](#getImages--) | प्रस्तुति में सभी चित्रों का संग्रह लौटाता है। |
| [getAudios()](#getAudios--) | प्रस्तुति में सभी अंतर्निहित ऑडियो फ़ाइलों का संग्रह लौटाता है। |
| [getVideos()](#getVideos--) | प्रस्तुति में सभी अंतर्निहित वीडियो फ़ाइलों का संग्रह लौटाता है। |
| [getSlideShowSettings()](#getSlideShowSettings--) | प्रस्तुति के स्लाइड शो सेटिंग्स लौटाता है। |
| [getDigitalSignatures()](#getDigitalSignatures--) | प्रस्तुति को साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। |
| [getCustomData()](#getCustomData--) | प्रस्तुति का कस्टम डेटा लौटाता है। |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | प्रस्तुति में सभी कस्टम डेटा भागों को लौटाता है। |
| [getVbaProject()](#getVbaProject--) | प्रेज़ेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त करता या सेट करता है। |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | प्रेज़ेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त करता या सेट करता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | सभी प्रस्तुति स्लाइडों (मास्टर, लेआउट, नोट्स स्लाइडों को छोड़कर) में मौजूद सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। |
| [getViewProperties()](#getViewProperties--) | प्रस्तुति-व्यापी दृश्य गुण प्राप्त करता है। |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | प्रस्तुति में पहले स्लाइड नंबर को दर्शाता है। |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | प्रस्तुति में पहले स्लाइड नंबर को दर्शाता है। |
| [getSensitivityLabels()](#getSensitivityLabels--) | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। |
| [getSlideById(long id)](#getSlideById-long-) | Id द्वारा एक Slide, MasterSlide या LayoutSlide लौटाता है। |
| [getSourceFormat()](#getSourceFormat--) | प्रस्तुति किस प्रारूप से लोड हुई, इसकी जानकारी लौटाता है। |
| [getMasterTheme()](#getMasterTheme--) | मास्टर थीम लौटाता है। |
| [save(String fname, int format)](#save-java.lang.String-int-) | निर्दिष्ट प्रारूप में एक फ़ाइल में प्रस्तुति की सभी स्लाइड्स सहेजता है। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | निर्दिष्ट प्रारूप में एक स्ट्रीम में प्रस्तुति की सभी स्लाइड्स सहेजता है। |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ एक फ़ाइल में प्रस्तुति की सभी स्लाइड्स सहेजता है। |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ एक स्ट्रीम में प्रस्तुति की सभी स्लाइड्स सहेजता है। |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में प्रस्तुति की सभी स्लाइड्स सहेजता है। |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | प्रस्तुति की सभी स्लाइड्स के लिए Image ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | प्रस्तुति की निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | कस्टम स्केलिंग के साथ प्रस्तुति की सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | कस्टम स्केलिंग के साथ प्रस्तुति की निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | निर्दिष्ट आकार के साथ प्रस्तुति की सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | निर्दिष्ट आकार के साथ प्रस्तुति की निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | पेज नंबर बनाए रखते हुए निर्दिष्ट प्रारूप में फ़ाइल में प्रस्तुति की निर्दिष्ट स्लाइड्स सहेजता है। |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | पेज नंबर बनाए रखते हुए निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ फ़ाइल में प्रस्तुति की निर्दिष्ट स्लाइड्स सहेजता है। |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | पेज नंबर बनाए रखते हुए निर्दिष्ट प्रारूप में स्ट्रीम में प्रस्तुति की निर्दिष्ट स्लाइड्स सहेजता है। |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | पेज नंबर बनाए रखते हुए निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में प्रस्तुति की निर्दिष्ट स्लाइड्स सहेजता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी स्लाइड्स में सभी स्वीकार्य आकारों के सभी पैराग्राफ में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| [dispose()](#dispose--) | इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [getPresentation()](#getPresentation--) | टेक्स्ट का पैरेंट प्रस्तुति लौटाता है। |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | निश्चित रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निश्चित रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है। |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | निश्चित रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |

### Presentation() {#Presentation--}
```
public Presentation()
```

यह कंस्ट्रक्टर शून्य से नई प्रस्तुति बनाता है। बनाई गई प्रस्तुति में एक खाली स्लाइड होती है।

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

यह कंस्ट्रक्टर शून्य से नई प्रस्तुति बनाता है। बनाई गई प्रस्तुति में एक खाली स्लाइड होती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | अतिरिक्त लोड विकल्प। |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के मुख्य तंत्र के रूप में कार्य करता है।

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

यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के मुख्य तंत्र के रूप में कार्य करता है।

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

दिनांक और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। यह प्रस्तुति ऑब्जेक्ट के निर्माण का समय है। पढ़ने/लिखने योग्य java.util.Date।

**रिटर्न:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

दिनांक और समय लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। यह प्रस्तुति ऑब्जेक्ट के निर्माण का समय है। पढ़ने/लिखने योग्य java.util.Date।

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
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible का उपयोग यह दर्शाने के लिए किया जाता है कि स्लाइड फुटर प्लेसहोल्डर मौजूद नहीं है.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility का उपयोग स्लाइड फुटर प्लेसहोल्डर को दिखाने के लिए किया जाता है.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible का उपयोग यह दर्शाने के लिए किया जाता है कि स्लाइड पेज नंबर प्लेसहोल्डर मौजूद नहीं है.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility का उपयोग स्लाइड पेज नंबर प्लेसहोल्डर को दिखाने के लिए किया जाता है.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible का उपयोग यह दर्शाने के लिए किया जाता है कि स्लाइड दिनांक-समय प्लेसहोल्डर मौजूद नहीं है.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetDateTimeVisibility का उपयोग स्लाइड दिनांक-समय प्लेसहोल्डर को दिखाने के लिए किया जाता है.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText का उपयोग स्लाइड फुटर प्लेसहोल्डर के लिए टेक्स्ट सेट करने के लिए किया जाता है.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText का उपयोग स्लाइड दिनांक-समय प्लेसहोल्डर के लिए टेक्स्ट सेट करने के लिए किया जाता है.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility का उपयोग मास्टर स्लाइड और सभी चाइल्ड फुटर प्लेसहोल्डर को दिखाने के लिए किया जाता है.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility का उपयोग मास्टर स्लाइड और सभी चाइल्ड पेज नंबर प्लेसहोल्डर को दिखाने के लिए किया जाता है.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility का उपयोग मास्टर स्लाइड और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर को दिखाने के लिए किया जाता है.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText का उपयोग मास्टर स्लाइड और सभी चाइल्ड फुटर प्लेसहोल्डर के लिए टेक्स्ट सेट करने के लिए किया जाता है.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText का उपयोग मास्टर स्लाइड और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर के लिए टेक्स्ट सेट करने के लिए किया जाता है.
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

इस प्रस्तुति के लिए अनुमतियों के प्रबंधक को प्राप्त करता है। केवल-पढ़ने योग्य [IProtectionManager](../../com.aspose.slides/iprotectionmanager)।

**रिटर्न:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

प्रेज़ेंटेशन में परिभाषित सभी स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [ISlideCollection](../../com.aspose.slides/islidecollection)।

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टैंशिएट करें
>  Presentation pres = new Presentation();
>  try
>  {
>      // पहले ISlide की पृष्ठभूमि का रंग नीला सेट करें
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
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टैंशिएट करें
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // इमेज के साथ पृष्ठभूमि सेट करें
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // चित्र सेट करें
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // प्रस्तुति की इमेज संग्रह में छवि जोड़ें
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // प्रस्तुति को डिस्क पर लिखें
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // स्रोत प्रस्तुति फ़ाइल लोड करने के लिए Presentation क्लास को इंस्टैंशिएट करें
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // स्लाइड 1 पर सर्कल प्रकार का ट्रांज़िशन लागू करें
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // स्लाइड 2 पर कॉम्ब प्रकार का ट्रांज़िशन लागू करें
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // प्रस्तुति को डिस्क पर लिखें
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टैंशिएट करें
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // स्लाइड 1 पर सर्कल प्रकार का ट्रांज़िशन लागू करें
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // ट्रांज़िशन समय 3 सेकंड सेट करें
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // स्लाइड 2 पर कॉम्ब प्रकार का ट्रांज़िशन लागू करें
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // ट्रांज़िशन समय 5 सेकंड सेट करें
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // स्लाइड 3 पर ज़ूम प्रकार का ट्रांज़िशन लागू करें
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // ट्रांज़िशन समय 7 सेकंड सेट करें
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // प्रस्तुति को डिस्क पर लिखें
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

प्रेज़ेंटेशन में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। केवल-पढ़ने योग्य [ISectionCollection](../../com.aspose.slides/isectioncollection)।

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
>      // section1 newSlide2 पर समाप्त होगा और उसके बाद section2 शुरू होगा
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
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट इंस्टैंशिएट करें
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // उत्पन्न प्रस्तुतियों का स्लाइड आकार स्रोत के समान सेट करें
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize का उपयोग स्केल किए हुए कंटेंट के साथ स्लाइड आकार सेट करने के लिए किया जाता है ताकि फिट सुनिश्चित हो
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize का उपयोग कंटेंट के अधिकतम आकार के साथ स्लाइड आकार सेट करने के लिए किया जाता है
>          // प्रस्तुति को डिस्क पर सहेजें
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 कागज आकार
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

प्रेज़ेंटेशन में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)।

--------------------

आप IMasterSlide.LayoutSlides प्रॉपर्टी का उपयोग करके लेआउट स्लाइड्स जोड़ने/डालने/हटाने/क्लोन करने के लिए वैकल्पिक API तक पहुंच सकते हैं।

**रिटर्न:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

प्रेज़ेंटेशन में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)।

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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

फ़ॉन्ट्स प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IFontsManager](../../com.aspose.slides/ifontsmanager)।

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // प्रस्तुति लोड करें
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // प्रतिस्थापित करने के लिए स्रोत फ़ॉन्ट लोड करें
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
>      // प्रस्तुति सहेजें
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

टिप्पणियों के लेखकों का संग्रह लौटाता है। केवल-पढ़ने योग्य [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)।

**रिटर्न:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

DocumentProperties ऑब्जेक्ट लौटाता है जो मानक और कस्टम दस्तावेज़ गुणों को शामिल करता है। केवल-पढ़ने योग्य [IDocumentProperties](../../com.aspose.slides/idocumentproperties)।

**रिटर्न:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

प्रेज़ेंटेशन में सभी चित्रों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IImageCollection](../../com.aspose.slides/iimagecollection)।

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // एक नई प्रस्तुति बनाता है जिसमे छवि जोड़ी जाएगी।
>  Presentation pres = new Presentation();
>  try
>  {
>      // मान लीजिए हमारे पास बड़ी छवि फ़ाइल है जिसे हम प्रस्तुति में शामिल करना चाहते हैं
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // चलिए छवि को प्रस्तुति में जोड़ते हैं - हम KeepLocked व्यवहार चुनते हैं क्योंकि हम
>          // "largeImage.png" फ़ाइल तक पहुंचने का इरादा नहीं रखते।
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // प्रस्तुति को सहेजता है। बड़ी प्रस्तुति आउटपुट होते समय, मेमोरी उपयोग
>          // pres ऑब्जेक्ट के जीवनकाल में कम रहता है।
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // छवि को प्रस्तुति में जोड़ता है
>          IPPImage image = pres.getImages().addImage(fos);
>          // पहले जोड़ी गई छवि के आधार पर स्लाइड 1 पर चित्र फ्रेम बनाता है
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

प्रेज़ेंटेशन में सभी अंतर्निहित ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAudioCollection](../../com.aspose.slides/iaudiocollection)।

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

प्रेज़ेंटेशन में सभी अंतर्निहित वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IVideoCollection](../../com.aspose.slides/ivideocollection)।

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // एक नई प्रस्तुति बनाता है जिसमें चित्र जोड़ी जाएगी।
>  Presentation pres = new Presentation();
>  try
>  {
>      // मान लेते हैं कि हमारे पास बड़ी छवि फ़ाइल है जिसे हम प्रस्तुति में शामिल करना चाहते हैं।
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // चलो चित्र को प्रस्तुति में जोड़ते हैं - हम KeepLocked व्यवहार चुनते हैं क्योंकि हम
>          // इसे "largeImage.png" फ़ाइल तक पहुंचने का इरादा नहीं रखते।
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // प्रस्तुति को सहेजता है। बड़ी प्रस्तुति आउटपुट होते समय, मेमोरी उपयोग
>          // pres ऑब्जेक्ट के जीवनकाल में कम रहता है।
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // छवि को प्रस्तुति में जोड़ता है।
>          IPPImage image = pres.getImages().addImage(fos);
>          // पहले जोड़ी गई छवि के आधार पर स्लाइड 1 पर चित्र फ्रेम बनाता है।
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

प्रेज़ेंटेशन के स्लाइड शो सेटिंग्स लौटाता है।

**रिटर्न:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

प्रेज़ेंटेशन को साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)।

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


**रिटर्न:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

प्रेज़ेंटेशन का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata)।

**रिटर्न:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

प्रेज़ेंटेशन में सभी कस्टम डेटा भागों को लौटाता है। केवल-पढ़ने योग्य ICustomXmlPart[]।

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // सभी कस्टम XML भागों पर इटरेट करें
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

**रिटर्न:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

प्रेज़ेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [IVbaProject](../../com.aspose.slides/ivbaproject)।

**रिटर्न:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

प्रेज़ेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [IVbaProject](../../com.aspose.slides/ivbaproject)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

सभी प्रस्तुति स्लाइडों (मास्टर, लेआउट, नोट्स स्लाइडों को छोड़कर) में मौजूद सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)।

**रिटर्न:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

प्रेज़ेंटेशन-व्यापी दृश्य गुण प्राप्त करता है। केवल-पढ़ने योग्य [IViewProperties](../../com.aspose.slides/iviewproperties)।

**रिटर्न:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

प्रेज़ेंटेशन में पहले स्लाइड नंबर को दर्शाता है

**रिटर्न:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

प्रेज़ेंटेशन में पहले स्लाइड नंबर को दर्शाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

प्रेज़ेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)।

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
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Id द्वारा एक Slide, MasterSlide या LayoutSlide लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | long | स्लाइड की Id। |

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide ऑब्जेक्ट।
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

प्रेज़ेंटेशन किस प्रारूप से लोड हुई, इसकी जानकारी लौटाता है। केवल-पढ़ने योग्य [SourceFormat](../../com.aspose.slides/sourceformat)।

**रिटर्न:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

मास्टर थीम लौटाता है। केवल-पढ़ने योग्य [IMasterTheme](../../com.aspose.slides/imastertheme)।

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला एक Presentation ऑब्जेक्ट इंस्टैंशिएट करें
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


**रिटर्न:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

सभी स्लाइड्स को निर्दिष्ट प्रारूप में फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाए गई फ़ाइल का पथ। |
| format | int | निर्यातित डेटा का प्रारूप। |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

सभी स्लाइड्स को निर्दिष्ट प्रारूप में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यातित डेटा का प्रारूप। |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

सभी स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाए गई फ़ाइल का पथ। |
| format | int | निर्यातित डेटा का प्रारूप। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त प्रारूप विकल्प। |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

सभी स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| format | int | निर्यातित डेटा का प्रारूप। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त प्रारूप विकल्प। |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML प्रारूप विकल्प। |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

प्रेज़ेंटेशन की सभी स्लाइड्स के लिए Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |

**रिटर्न:**
com.aspose.slides.IImage[] - Image ऑब्जेक्ट्स।
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |

**रिटर्न:**
com.aspose.slides.IImage[] - Image ऑब्जेक्ट्स।
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

सभी स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| scaleX | float | X-अक्ष दिशा में स्केल करने का मान। |
| scaleY | float | Y-अक्ष दिशा में स्केल करने का मान। |

**रिटर्न:**
com.aspose.slides.IImage[] - Image ऑब्जेक्ट्स।
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

निर्दिष्ट स्लाइडों के लिए कस्टम स्केलिंग के साथ थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |
| scaleX | float | X-अक्ष दिशा में स्केल करने का मान। |
| scaleY | float | Y-अक्ष दिशा में स्केल करने का मान। |

**रिटर्न:**
com.aspose.slides.IImage[] - Image ऑब्जेक्ट्स।
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

निर्दिष्ट आकार के साथ सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| imageSize | [Size](../../com.aspose.slides.android/size) | बनाई जाने वाली इमेज का आकार। |

**रिटर्न:**
com.aspose.slides.IImage[] - Image ऑब्जेक्ट्स।
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

निर्दिष्ट स्लाइडों के लिए निर्दिष्ट आकार के साथ थंबनेल Image ऑब्जेक्ट्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff विकल्प। |
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |
| imageSize | [Size](../../com.aspose.slides.android/size) | बनाई जाने वाली इमेज का आकार। |

**रिटर्न:**
com.aspose.slides.IImage[] - Image ऑब्जेक्ट्स।
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट प्रारूप में फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाए गई फ़ाइल का पथ। |
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |
| format | int | निर्यातित डेटा का प्रारूप। |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बनाए गई फ़ाइल का पथ। |
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |
| format | int | निर्यातित डेटा का प्रारूप। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त प्रारूप विकल्प। |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट स्वरूप में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |
| format | int | निर्यातित डेटा का स्वरूप। |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट स्वरूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
| slides | int[] | स्लाइड स्थितियों की सूची, 1 से शुरू। |
| format | int | निर्यातित डेटा का स्वरूप। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त स्वरूप विकल्प। |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

सभी स्लाइड्स में सभी स्वीकार्य आकारों के सभी पैराग्राफ में समान फॉर्मेटिंग वाले रन को जोड़ता है।

### dispose() {#dispose--}
```
public final void dispose()
```

इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है।

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

टेक्स्ट का पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

निश्चित रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // सभी अलग-अलग 'the' की घटनाओं को हाइलाइट करना
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
| highlightColor | java.lang.Integer | टेक्स्ट को हाइलाइट करने का रंग। |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

निश्चित रंग के साथ नमूना टेक्स्ट के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' घटनाओं को हाइलाइट करना
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
| highlightColor | java.lang.Integer | टेक्स्ट को हाइलाइट करने का रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

निश्चित रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10 प्रतीकों या उससे अधिक वाले सभी शब्दों को हाइलाइट करना
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिए नियमित अभिव्यक्ति। |
| highlightColor | java.lang.Integer | टेक्स्ट को हाइलाइट करने का रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है।

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| newText | java.lang.String | पुरानी स्ट्रिंग की सभी घटनाओं को बदलने के लिए स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
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
>      // 10 प्रतीकों या उससे अधिक वाले सभी शब्दों को '***' से बदलें
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिए नियमित अभिव्यक्ति। |
| newText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |