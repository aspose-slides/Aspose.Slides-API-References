---
title: SlideCollection
second_title: Aspose.Slides for Java API संदर्भ
description: स्लाइड्स के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/slidecollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

स्लाइड्स का एक संग्रह दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | निर्दिष्ट स्लाइड की एक प्रति निर्दिष्ट अनुभाग के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | संग्रह के अंत में एक नया खाली स्लाइड जोड़ता है। |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | संग्रह से किसी विशिष्ट ऑब्जेक्ट की पहली प्रविष्टि को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटरेटर लौटाता है। |
| [toArray()](#toArray--) | सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा से सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है। |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | स्लाइड को संग्रह से निर्दिष्ट स्थान पर ले जाता है। |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | संग्रह से स्लाइड्स को निर्दिष्ट स्थान पर ले जाता है। |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमणिका लौटाता है। |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और PDF आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच सिंक्रनाइज़्ड है (थ्रेड-सेफ़)। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int.

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [Slide](../../com.aspose.slides/slide)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन हो सकता है। आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि एक ही मास्टर स्लाइड के कई क्लोन बनने से बचा जा सके। मैनुअल रूप से मास्टर स्लाइड को क्लोन करना न तो रोका जाता है न ही पंजीकृत किया जाता है। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) या \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) का उपयोग करें स्लाइड्स को क्लोन करने के लिए, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) या [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) लेआउट को क्लोन करने के लिए और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर को क्लोन करने के लिए।

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
>      // अब दूसरा सेक्शन पहले स्लाइड की एक प्रतिलिपि रखता है।
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| section | [ISection](../../com.aspose.slides/isection) | नए स्लाइड के लिए अनुभाग। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

निर्दिष्ट स्थान पर निर्दिष्ट स्लाइड की एक प्रति संग्रह में सम्मिलित करता है।

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Presentation क्लास को इंस्टैंशिएट करें जो एक प्रेजेंटेशन फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // इच्छित स्लाइड को उसी प्रेजेंटेशन में स्लाइड्स के संग्रह के अंत में क्लोन करें
>      ISlideCollection slds = pres.getSlides();
>      // इच्छित स्लाइड को उसी प्रेजेंटेशन में निर्दिष्ट इंडेक्स पर क्लोन करें
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // संशोधित प्रेजेंटेशन को डिस्क पर लिखें
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // स्रोत प्रेजेंटेशन फ़ाइल लोड करने के लिए Presentation क्लास को इंस्टैंशिएट करें
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // गंतव्य PPTX (जहाँ स्लाइड को क्लोन किया जाना है) के लिए Presentation क्लास को इंस्टैंशिएट करें
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // गंतव्य प्रेजेंटेशन को डिस्क पर लिखें
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमणिका। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन हो सकता है। आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि एक ही मास्टर स्लाइड के कई क्लोन बनने से बचा जा सके। मैनुअल रूप से मास्टर स्लाइड को क्लोन करना न तो रोका जाता है न ही पंजीकृत किया जाता है। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) या \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) का उपयोग करें स्लाइड्स को क्लोन करने के लिए और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर को क्लोन करने के लिए।

**Returns:**
[ISlide](../../com.aspose.slides/islide) - डालित स्लाइड।

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

संग्रह के अंत में एक नया खाली स्लाइड जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिए लेआउट। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - जोड़ी गई स्लाइड।

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

निर्दिष्ट स्थान पर निर्दिष्ट स्लाइड की एक प्रति संग्रह में सम्मिलित करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमणिका। |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिए लेआउट। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - डालित स्लाइड।

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नए स्लाइड के लिए लेआउट स्लाइड। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्थान पर निर्दिष्ट स्लाइड की एक प्रति संग्रह में सम्मिलित करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमणिका। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नए स्लाइड के लिए लेआउट स्लाइड। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - डालित स्लाइड।

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट मास्टर से चुना जाएगा (उपयुक्त लेआउट वही लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि false)। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्थान पर निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह में सम्मिलित करता है। उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट मास्टर से चुना जाएगा (उपयुक्त लेआउट वही लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमणिका। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए स्लाइड के लिए मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि false)। |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - डालित स्लाइड।

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

संग्रह से किसी विशिष्ट ऑब्जेक्ट की पहली प्रविष्टि को हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | संग्रह से हटाने के लिए स्लाइड। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमणिका। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरट करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

पूरे संग्रह के लिए जावा इटरेटर लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - एक java.util.Iterator पूरे संग्रह के लिए।

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है।

**Returns:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा से सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | पहली स्लाइड का अनुक्रमणिका। |
| count | int | जोड़ने के लिए स्लाइड्स की संख्या। |

**Returns:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

स्लाइड को संग्रह से निर्दिष्ट स्थिति में ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| slide | [ISlide](../../com.aspose.slides/islide) | स्थानांतरित करने के लिए स्लाइड। |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। स्लाइड्स को सूची में उनके क्रम के अनुसार इंडेक्स से शुरू करके रखा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | स्थानांतरित करने के लिए स्लाइड्स। |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | खोजने के लिए स्लाइड। |

**रिटर्न:**
int - स्लाइड का अनुक्रमांक, या -1 यदि स्लाइड इस संग्रह से नहीं है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पथ |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है, PDF आयात विकल्पों को ध्यान में रखते हुए।

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
| path | java.lang.String | PDF दस्तावेज़ का पथ |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF आयात के विकल्प |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

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
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF आयात के विकल्प |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। यदि यह पैरामिटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक्स को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स।

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम ऑब्जेक्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। यदि यह पैरामिटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक्स को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स।

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

--------------------

> ```
> // Presentation क्लास का एक इंस्टैंस बनाएं।
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // AddFromHtml मेथड को कॉल करें और HTML फ़ाइल पास करें।
>      pres.getSlides().addFromHtml(html);
>      // फ़ाइल को PowerPoint दस्तावेज़ के रूप में सहेजने के लिए Save मेथड का उपयोग करें।
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम ऑब्जेक्ट। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। यदि यह पैरामिटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक्स को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स।

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। यदि यह पैरामिटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक्स को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू किया जाए: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स।

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlText | java.lang.String | जोड़ने के लिए HTML। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन जहाँ से शुरू किया जाए: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम ऑब्जेक्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। यदि यह पैरामिटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक्स को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स।

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम ऑब्जेक्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। यदि यह पैरामिटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक्स को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू किया जाए: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स।

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम ऑब्जेक्ट। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डालने की स्थिति। |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम ऑब्जेक्ट। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कहाँ से शुरू किया जाए: नई स्लाइड से या निर्दिष्ट अनुक्रमांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट अनुक्रमांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुँच का समकालिक (थ्रेड-सेफ़) है या नहीं, यह दर्शाता हुआ मान लौटाता है। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समकालिक मूल लौटाता है। केवल-पढ़ने योग्य ऑब्जेक्ट।

**रिटर्न:**
java.lang.Object