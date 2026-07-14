---
title: ISlideCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक स्लाइड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/islidecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

एक स्लाइड्स का संग्रह का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | निर्दिष्ट स्लाइड की एक कॉपी निर्दिष्ट अनुभाग के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | एक नया खाली स्लाइड संग्रह के अंत में जोड़ता है। |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | संग्रह से विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [toArray()](#toArray--) | सभी स्लाइड्स के साथ एक एरे बनाता है और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट रेंज से सभी स्लाइड्स के साथ एक एरे बनाता है और लौटाता है। |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | स्लाइड को संग्रह से निर्दिष्ट स्थिति में ले जाता है। |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है। |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड बनाता है और PDF इम्पोर्ट विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रेजेंटेशन के बीच स्लाइड क्लोन की जाती है तो स्लाइड के मास्टर को भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए प्रयुक्त होती है ताकि समान मास्टर स्लाइड के कई क्लोन बनने से रोका जा सके। मास्टर स्लाइड का मैन्युअल क्लोनिंग न तो रोका जाता है न ही रजिस्टर्ड किया जाता है। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) या \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) का उपयोग करें स्लाइड्स को क्लोन करने के लिए, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) या [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) लेआउट को क्लोन करने के लिए और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर को क्लोन करने के लिए। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

निर्दिष्ट स्लाइड की एक कॉपी निर्दिष्ट अनुभाग के अंत में जोड़ता है।

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // अब दूसरा सेक्शन पहले स्लाइड की एक कॉपी रखता है।
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| section | [ISection](../../com.aspose.slides/isection) | नई स्लाइड के लिए अनुभाग। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

निर्दिष्ट स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रेजेंटेशन के बीच स्लाइड क्लोन की जाती है तो स्लाइड के मास्टर को भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए प्रयुक्त होती है ताकि समान मास्टर स्लाइड के कई क्लोन बनने से रोका जा सके। मास्टर स्लाइड का मैन्युअल क्लोनिंग न तो रोका जाता है न ही रजिस्टर्ड किया जाता है। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) या \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) का उपयोग करें स्लाइड्स को क्लोन करने के लिए और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर को क्लोन करने के लिए। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

एक नया खाली स्लाइड संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिए लेआउट। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - जोड़ी गई स्लाइड।

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

निर्दिष्ट स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिए लेआउट। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नई स्लाइड के लिए लेआउट स्लाइड। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नई स्लाइड के लिए लेआउट स्लाइड। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्रोत स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चयन किया जायेगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं मिला तो स्रोत स्लाइड का लेआउट क्लोन किया जायेगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जायेगा (यदि allowCloneMissingLayout false है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जायेगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जायेगा (यदि allowCloneMissingLayout false है)। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्रोत स्लाइड की एक कॉपी संग्रह के निर्दिष्ट स्थिति में सम्मिलित करता है। उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चयन किया जायेगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं मिला तो स्रोत स्लाइड का लेआउट क्लोन किया जायेगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जायेगा (यदि allowCloneMissingLayout false है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जायेगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जायेगा (यदि allowCloneMissingLayout false है)। |

**रिटर्न मान:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

संग्रह से विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | हटाने के लिए स्लाइड। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

सभी स्लाइड्स के साथ एक एरे बनाता है और लौटाता है।

**रिटर्न मान:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) का एरे

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

निर्दिष्ट रेंज से सभी स्लाइड्स के साथ एक एरे बनाता है और लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | जोड़ने के लिए पहली स्लाइड का अनुक्रमांक। |
| count | int | जोड़ने के लिए स्लाइड्स की संख्या। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) का एरे

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

स्लाइड को संग्रह से निर्दिष्ट स्थिति में ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| slide | [ISlide](../../com.aspose.slides/islide) | ले जाने वाली स्लाइड। |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। स्लाइड्स को सूची में दिखाई देने के क्रम में अनुक्रमांक से शुरू होते हुए रखा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | ले जाने वाली स्लाइड्स। |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | खोजने वाली स्लाइड। |

**रिटर्न मान:**
int - स्लाइड का अनुक्रमांक या -1 यदि स्लाइड इस संग्रह की नहीं है।

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> उदाहरण:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पाथ |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF दस्तावेज़ से स्लाइड बनाता है और PDF इम्पोर्ट विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पाथ |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF इम्पोर्ट के विकल्प |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF इम्पोर्ट के विकल्प |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ अनदेखी की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | java.io.InputStream | स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम जो HTML फ़ाइल को प्रस्तुत करता है। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ अनदेखी की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | java.io.InputStream | स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम जो HTML फ़ाइल को प्रस्तुत करता है। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ अनदेखी की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlStream | java.io.InputStream | स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम जो HTML फ़ाइल को प्रस्तुत करता है। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ अनदेखी की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlStream | java.io.InputStream | स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम जो HTML फ़ाइल को प्रस्तुत करता है। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| useSlideWithIndexAsStart | boolean | यह फ्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू हो: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जायेगा। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ अनदेखी की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू हो: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जायेगा। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlStream | java.io.InputStream | स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम जो HTML फ़ाइल को प्रस्तुत करता है। |
| useSlideWithIndexAsStart | boolean | यह फ्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू हो: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जायेगा। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने का स्थान। |
| htmlStream | java.io.InputStream | स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम जो HTML फ़ाइल को प्रस्तुत करता है। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ अनदेखी की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू हो: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जायेगा। |

**रिटर्न मान:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।