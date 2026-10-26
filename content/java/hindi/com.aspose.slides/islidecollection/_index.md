---
title: ISlideCollection
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: स्लाइड्स के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/islidecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

स्लाइड्स का संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | निर्दिष्ट स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है। |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | निर्दिष्ट अनुभाग के अंत में निर्दिष्ट स्लाइड की एक प्रतिलिपि जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक प्रतिलिपि सम्मिलित करता है। |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | संग्रह के अंत में नया खाली स्लाइड जोड़ता है। |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक प्रतिलिपि सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक प्रतिलिपि सम्मिलित करता है। |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | निर्दिष्ट स्रोत स्लाइड की एक प्रतिलिपि को संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | संग्रह से एक विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [toArray()](#toArray--) | सभी स्लाइड्स को समाहित करता हुआ एक एरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा से सभी स्लाइड्स को समाहित करता हुआ एक एरे बनाता और लौटाता है। |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | स्लाइड को संग्रह से निर्दिष्ट स्थिति पर ले जाता है। |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | स्लाइड्स को संग्रह से निर्दिष्ट स्थिति पर ले जाता है। स्लाइड्स को अनुक्रमांक से शुरू करके सूची में दिखाई देने के क्रम में रखा जाएगा। |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है। |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF आयात विकल्पों को ध्यान में रखते हुए PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML पाठ से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

निर्दिष्ट स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री का उपयोग स्वतः क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से बचा जा सके। मास्टर स्लाइड्स का मैनुअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड होगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) या \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) का उपयोग करें स्लाइड्स को क्लोन करने के लिये, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) या [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) लेआउट को क्लोन करने के लिये और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर को क्लोन करने के लिये।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

निर्दिष्ट स्लाइड की एक प्रतिलिपि निर्दिष्ट अनुभाग के अंत में जोड़ता है।

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
>      // अब दूसरा सेक्शन पहली स्लाइड की एक कॉपी रखता है।
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| section | [ISection](../../com.aspose.slides/isection) | नए स्लाइड के लिये अनुभाग। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक प्रतिलिपि सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच स्लाइड को क्लोन किया जाता है तो स्लाइड का मास्टर भी क्लोन किया जा सकता है। आंतरिक रजिस्ट्री का उपयोग स्वतः क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से बचा जा सके। मास्टर स्लाइड्स का मैनुअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड होगा। यदि आपको क्लोनिंग प्रक्रिया पर अधिक नियंत्रण चाहिए तो \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) या \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) का उपयोग करें स्लाइड्स को क्लोन करने के लिये और [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) मास्टर को क्लोन करने के लिये।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

संग्रह के अंत में नया खाली स्लाइड जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिये लेआउट। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - जोड़ा गया स्लाइड।

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक प्रतिलिपि सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमांक। |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्लाइड के लिये लेआउट। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नए स्लाइड के लिये लेआउट स्लाइड। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्लाइड की एक प्रतिलिपि सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | नए स्लाइड के लिये लेआउट स्लाइड। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट स्रोत स्लाइड की एक प्रतिलिपि संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट को निर्दिष्ट मास्टर से स्वतः चयन किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए स्लाइड के लिये मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - नया स्लाइड।

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

निर्दिष्ट संग्रह में निर्दिष्ट स्थिति पर निर्दिष्ट स्रोत स्लाइड की एक प्रतिलिपि सम्मिलित करता है। उपयुक्त लेआउट को निर्दिष्ट मास्टर से स्वतः चयन किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमांक। |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | क्लोन करने के लिये स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए स्लाइड के लिये मास्टर स्लाइड। |
| allowCloneMissingLayout | boolean | यदि निर्दिष्ट मास्टर में उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide) - सम्मिलित स्लाइड।

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

संग्रह से एक विशिष्ट वस्तु की पहली घटना को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | संग्रह से हटाने के लिये स्लाइड। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

सभी स्लाइड्स को समाहित करता हुआ एक एरे बनाता और लौटाता है।

**रिटर्न:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा से सभी स्लाइड्स को समाहित करता हुआ एक एरे बनाता और लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | पहले जोड़ने वाले स्लाइड का अनुक्रमांक। |
| count | int | जोड़ने के लिये स्लाइड्स की संख्या। |

**रिटर्न:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

स्लाइड को संग्रह से निर्दिष्ट स्थिति पर ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| slide | [ISlide](../../com.aspose.slides/islide) | स्थानांतरित करने के लिये स्लाइड। |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

स्लाइड्स को संग्रह से निर्दिष्ट स्थिति पर ले जाता है। स्लाइड्स को अनुक्रमांक से शुरू करके सूची में दिखाई देने के क्रम में रखा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | जाने के लिये स्लाइड्स। |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | खोजने के लिये स्लाइड। |

**रिटर्न:**
int - स्लाइड का अनुक्रमांक या -1 यदि स्लाइड इस संग्रह से नहीं है।

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पथ |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF दस्तावेज़ से स्लाइड्स बनाता है और PDF आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है।

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


**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | PDF दस्तावेज़ का पथ |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF आयात के विकल्प |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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


**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF आयात के विकल्प |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
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


**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF दस्तावेज़ के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | जोड़ने के लिए HTML |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlText | java.lang.String | जोड़ने के लिए HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlText | java.lang.String | जोड़ने के लिए HTML |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlText | java.lang.String | जोड़ने के लिए HTML |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से। यदि **true** हो तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** हो तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlText | java.lang.String | जोड़ने के लिए HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से। यदि **true** हो तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** हो तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से। यदि **true** हो तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** हो तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

**पैरामीटर्स:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | इन्सर्ट करने की स्थिति |
| htmlStream | java.io.InputStream | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाने वाला स्ट्रीम ऑब्जेक्ट |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | java.lang.String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | boolean | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से। यदि **true** हो तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** हो तो डेटा निर्मित स्लाइड्स में जोड़ा जाएगा। |

**रिटर्न:**  
com.aspose.slides.ISlide[] - जोड़े गए स्लाइड्स.