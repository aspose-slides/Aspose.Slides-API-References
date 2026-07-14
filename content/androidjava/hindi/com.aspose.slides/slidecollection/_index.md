---
title: SlideCollection
second_title: Aspose.Slides for Android via Java API संदर्भ
description: स्लाइड्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/slidecollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

स्लाइड्स का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | निर्दिष्ट स्लाइड की एक प्रति निर्दिष्ट अनुभाग के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | संग्रह के अंत में एक नया खाली स्लाइड जोड़ता है। |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | संग्रह से विशिष्ट वस्तु की पहली आवृत्ति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |
| [toArray()](#toArray--) | सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट रेंज से सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है। |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | संग्रह से स्लाइड को निर्दिष्ट स्थिति पर ले जाता है। |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | संग्रह से स्लाइड्स को निर्दिष्ट स्थिति पर ले जाता है। |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है। |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और pdf आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि क्या संग्रह का अभिगमन समकालिक (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [Slide](../../com.aspose.slides/slide).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच एक स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री का उपयोग स्वतः क्लोन किए गए मास्टर्स को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से रोका जा सके। मास्टर स्लाइड्स का मैन्युअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड होगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) या \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) का उपयोग करके स्लाइड्स को क्लोन करें, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) या [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) लेआउट्स को क्लोन करने के लिए और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर्स को क्लोन करने के लिए। 

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

निर्दिष्ट स्लाइड की एक प्रति निर्दिष्ट अनुभाग के अंत में जोड़ता है।

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
>      // अब दूसरे सेक्शन में पहली स्लाइड की एक प्रति शामिल है।
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| section | [ISection](../../com.aspose.slides/isection) | नई स्लाइड के लिए अनुभाग। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation क्लास बनाएं
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // इच्छित स्लाइड को उसी प्रस्तुति में स्लाइड्स के संग्रह के अंत में क्लोन करें
>      ISlideCollection slds = pres.getSlides();
>      // इच्छित स्लाइड को उसी प्रस्तुति में निर्दिष्ट अनुक्रमांक पर क्लोन करें
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // संशोधित प्रस्तुति को डिस्क पर लिखें
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // स्रोत प्रस्तुति फ़ाइल लोड करने के लिए Presentation क्लास बनाएं
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // लक्ष्य PPTX (जहाँ स्लाइड को क्लोन किया जाएगा) के लिए Presentation क्लास बनाएं
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // लक्ष्य प्रस्तुति को डिस्क पर लिखें
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच एक स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री का उपयोग स्वतः क्लोन किए गए मास्टर्स को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से रोका जा सके। मास्टर स्लाइड्स का मैन्युअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड होगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) या \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) का उपयोग करके स्लाइड्स को क्लोन करें और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) को मास्टर क्लोन करने के लिए। 

**Returns:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

संग्रह के अंत में एक नया खाली स्लाइड जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिए लेआउट। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - जोड़ी गई स्लाइड।

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिए लेआउट। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नई स्लाइड के लिए लेआउट स्लाइड। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नई स्लाइड के लिए लेआउट स्लाइड। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चयनित किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चयनित किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

संग्रह से विशिष्ट वस्तु की पहली आवृत्ति को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | संग्रह से हटाने के लिए स्लाइड। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - एक IGenericEnumerator जिसे संग्रह के माध्यम से पुनरावृत्ति करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - पूरे संग्रह के लिए java.util.Iterator।

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है।

**Returns:**
com.aspose.slides.ISlide[] - एरे जिसमें [Slide](../../com.aspose.slides/slide) है

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

निर्दिष्ट रेंज से सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | जोड़ने के लिए पहले स्लाइड का अनुक्रमांक। |
| count | int | जोड़ने के लिए स्लाइड्स की संख्या। |

**Returns:**
com.aspose.slides.ISlide[] - एरे जिसमें [Slide](../../com.aspose.slides/slide) है

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

संग्रह से स्लाइड को निर्दिष्ट स्थिति पर ले जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्षित अनुक्रमांक। |
| slide | [ISlide](../../com.aspose.slides/islide) | ले जाने वाली स्लाइड। |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

स्लाइड्स को संग्रह से निर्दिष्ट स्थिति पर ले जाता है। स्लाइड्स सूची में दिखाई देने के क्रम में अनुक्रमांक से शुरू करके रखी जाएँगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्षित अनुक्रमांक। |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) |  |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | ढूँढ़ने के लिए स्लाइड। |

**Returns:**
int - स्लाइड का अनुक्रमांक या -1 यदि स्लाइड इस संग्रह से नहीं है।

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पथ। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और pdf आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> उदाहरण:
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


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पथ। |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF आयात के विकल्प। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> उदाहरण:
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


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

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

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम। |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF आयात के विकल्प। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ नजरअंदाज की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ नजरअंदाज की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> // Presentation क्लास की एक इंस्टेंस बनाएं।
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // AddFromHtml मेथड को कॉल करें और HTML फ़ाइल पास करें।
>          pres.getSlides().addFromHtml(fos);
>          // Save मेथड का उपयोग करके फ़ाइल को PowerPoint दस्तावेज़ के रूप में सेव करें।
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ नजरअंदाज की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ नजरअंदाज की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलित करना नई स्लाइड से शुरू किया जाए या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलित करना नई स्लाइड से शुरू किया जाए या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ नजरअंदाज की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुएँ नजरअंदाज की जाएँगी। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलित करना नई स्लाइड से शुरू किया जाए या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स।

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट। |

**Returns:**
com.aspose.slides.ISlide[] - जोड़ी गई स्लाइड्स

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति में संग्रह में सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सम्मिलित करने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलित करना नई स्लाइड से शुरू किया जाए या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

**Returns:**
com.aspose.slides.ISSlide[] - जोड़ी गई स्लाइड्स

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्वों की प्रतिलिपि निर्दिष्ट एरे में बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच समकालिक (थ्रेड-सेफ़) है। केवल-पढ़ने योग्य boolean.

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक मूल लौटाता है। केवल-पढ़ने योग्य Object.

**Returns:**
java.lang.Object