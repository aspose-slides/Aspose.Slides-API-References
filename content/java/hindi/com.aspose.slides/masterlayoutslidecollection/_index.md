---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides for Java API संदर्भ
description: परिभाषित मास्टर स्लाइड की सभी लेआउट स्लाइडों का संग्रह दर्शाता है।
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

परिभाषित मास्टर स्लाइड के सभी लेआउट स्लाइडों के संग्रह का प्रतिनिधित्व करता है। LayoutSlideCollection वर्ग को विस्तारित करता है जिसमें लेआउट स्लाइडों को जोड़ने/डालने/हटाने/क्लोन करने/पुनः क्रमित करने के लिए विधियां हैं, जो मास्टर की व्यक्तिगत लेआउट स्लाइड संग्रह के संदर्भ में हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर डालता है। |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | एक नया लेआउट स्लाइड संग्रह के अंत में जोड़ता है। |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | एक नया लेआउट स्लाइड संग्रह के निर्दिष्ट स्थान में डालता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह के निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है। |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | लेआउट स्लाइड को संग्रह से निर्दिष्ट स्थान पर ले जाता है। |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

1) नया लेआउट इस लेआउट स्लाइड संग्रह के पैरेंट मास्टर स्लाइड से जुड़ा होगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 2) इस विधि का समतुल्य विधि [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) है जिसे ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी द्वारा एक्सेस किया जाता है।

**रिटर्न:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमणिका। |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

नया लेआउट इस लेआउट स्लाइड संग्रह के पैरेंट मास्टर स्लाइड से जुड़ा होगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।

**रिटर्न:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - डाली गई स्लाइड।

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

एक नया लेआउट स्लाइड संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layoutType | byte | एक नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अभी अन्य लेआउट प्रकार समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | एक नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से दिए गए लेआउट प्रकार के आधार पर निर्मित होगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

1) लेआउट प्रकार SlideLayoutType.Custom के मान के लिए जोड़ा गया लेआउट कोई प्लेसहोल्डर और कोई आकार नहीं रखता है। 2) इस विधि का समतुल्य विधि [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) है जिसे ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी द्वारा एक्सेस किया जाता है।

**रिटर्न:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

एक नया लेआउट स्लाइड संग्रह के निर्दिष्ट स्थान पर डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमणिका। |
| layoutType | byte | एक नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अभी अन्य लेआउट प्रकार समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | एक नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से दिए गए लेआउट प्रकार के आधार पर निर्मित होगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

SlideLayoutType.Custom मान के लिए डाला गया लेआउट कोई प्लेसहोल्डर और कोई आकार नहीं रखता है।

**रिटर्न:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - डाली गई स्लाइड।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह के निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमणिका। |

--------------------

1) PptxEditException को फेंकने से बचने के लिए लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) विधि का भी उपयोग कर सकते हैं।

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

लेआउट स्लाइड को संग्रह से निर्दिष्ट स्थान पर ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमणिका। |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | ले जाने के लिए स्लाइड। |