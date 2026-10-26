---
title: MasterLayoutSlideCollection
second_title: Java API संदर्भ के माध्यम से Android के लिए Aspose.Slides
description: परिभाषित मास्टर स्लाइड की सभी लेआउट स्लाइडों के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/masterlayoutslidecollection/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)  
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

परिभाषित मास्टर स्लाइड के सभी लेआउट स्लाइड का संग्रह दर्शाता है। LayoutSlideCollection क्लास को विस्तारित करता है जिसमें मास्टर स्लाइड के व्यक्तिगत संग्रह के संदर्भ में लेआउट स्लाइड को जोड़ने/इन्सर्ट करने/हटाने/क्लोन करने/पुनःक्रमित करने के लिए मेथड्स होते हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | कलेक्शन के अंत में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है। |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | कलेक्शन में निर्दिष्ट स्थिति पर निर्दिष्ट लेआउट स्लाइड की एक प्रति डालता है। |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | कलेक्शन के अंत में एक नया लेआउट स्लाइड जोड़ता है। |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | कलेक्शन में निर्दिष्ट स्थिति पर नया लेआउट स्लाइड डालता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन के निर्दिष्ट इंडेक्स पर स्थित तत्व को हटाता है। |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | कलेक्शन से लेआउट स्लाइड को निर्दिष्ट स्थिति पर ले जाता है। |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

कलेक्शन के अंत में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

1) नया लेआउट इस लेआउट स्लाइड्स संग्रह के पैरेंट मास्टर स्लाइड के साथ जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 2) इस मेथड का समानांतर मेथड [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) है जिसे ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी द्वारा एक्सेस किया जाता है।

**रिटर्न्स:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ा गया स्लाइड।

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

कलेक्शन में निर्दिष्ट स्थिति पर निर्दिष्ट लेआउट स्लाइड की एक प्रति डालता है।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का इंडेक्स। |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

नया लेआउट इस लेआउट स्लाइड्स संग्रह के पैरेंट मास्टर स्लाइड के साथ जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।

**रिटर्न्स:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - इन्सर्ट किया गया स्लाइड।

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

कलेक्शन के अंत में एक नया लेआउट स्लाइड जोड़ता है।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layoutType | byte | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पास किया गया तो लेआउट प्रकार के आधार पर नाम स्वतः उत्पन्न किया जाएगा (उदा. "Title Slide" या "1_Title Slide", "2_.." आदि)। |

--------------------

1) लेआउटटाइप के मान SlideLayoutType.Custom के लिए जोड़ा गया लेआउट कोई प्लेसहोल्डर और कोई शैप नहीं रखता। 2) इस मेथड का समानांतर मेथड [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) है जिसे ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी द्वारा एक्सेस किया जाता है।

**रिटर्न्स:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ा गया स्लाइड।

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

कलेक्शन में निर्दिष्ट स्थिति पर नया लेआउट स्लाइड डालता है।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का इंडेक्स। |
| layoutType | byte | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पास किया गया तो लेआउट प्रकार के आधार पर नाम स्वतः उत्पन्न किया जाएगा (उदा. "Title Slide" या "1_Title Slide", "2_.." आदि)। |

--------------------

SlideLayoutType.Custom मान के लिए इन्सर्ट किया गया लेआउट कोई प्लेसहोल्डर और कोई शैप नहीं रखता।

**रिटर्न्स:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - इन्सर्ट किया गया स्लाइड।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

कलेक्शन के निर्दिष्ट इंडेक्स पर स्थित तत्व को हटाता है।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित इंडेक्स। |

--------------------

1) PptxEditException को फेंके जाने से बचने के लिए layout की HasDependingSlides प्रॉपर्टी को पहले जाँचें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) मेथड का भी उपयोग कर सकते हैं।

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

कलेक्शन से लेआउट स्लाइड को निर्दिष्ट स्थिति पर ले जाता है।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य इंडेक्स। |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | हिलाने के लिए स्लाइड। |