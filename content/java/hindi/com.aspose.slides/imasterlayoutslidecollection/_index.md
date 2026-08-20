---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides for Java API संदर्भ
description: परिभाषित मास्टर स्लाइड की सभी लेआउट स्लाइड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imasterlayoutslidecollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

परिभाषित मास्टर स्लाइड की सभी लेआउट स्लाइड्स का संग्रह दर्शाता है। ILayoutSlideCollection इंटरफ़ेस को विस्तारित करता है जिसमें व्यक्तिगत मास्टर लेआउट स्लाइड्स के संग्रह के संदर्भ में लेआउट स्लाइड्स को जोड़ने/इन्सर्ट करने/हटाने/क्लोन करने के लिए मेथड्स होते हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | नई लेआउट स्लाइड को संग्रह के अंत में जोड़ता है। |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | नई लेआउट स्लाइड को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट इंडेक्स पर तत्व को हटाता है। |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | संग्रह से लेआउट स्लाइड को निर्दिष्ट स्थान पर ले जाता है। |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

1) नया लेआउट इस लेआउट स्लाइड्स संग्रह के लिए पैरेंट मास्टर स्लाइड से जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट का समान है। 2) इस मेथड का समकक्ष मेथड [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) है जिसे [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का इंडेक्स। |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

नया लेआउट इस लेआउट स्लाइड्स संग्रह के लिए पैरेंट मास्टर स्लाइड से जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट का समान है। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - सम्मिलित स्लाइड।

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

नई लेआउट स्लाइड को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layoutType | byte | एक नई लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नई लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो नाम पास किए गए लेआउट प्रकार के आधार पर स्वचालित रूप से उत्पन्न किया जाएगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

1) layoutType के मूल्य SlideLayoutType.Custom के लिए जोड़ी गई लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं होते हैं। 2) इस मेथड का समकक्ष मेथड [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) है जिसे [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

नई लेआउट स्लाइड को संग्रह के निर्दिष्ट स्थान पर सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई स्लाइड का इंडेक्स। |
| layoutType | byte | एक नई लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नई लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो नाम पास किए गए लेआउट प्रकार के आधार पर स्वचालित रूप से उत्पन्न किया जाएगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

layoutType के मूल्य SlideLayoutType.Custom के लिए सम्मिलित लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं होते हैं। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - सम्मिलित स्लाइड।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट इंडेक्स पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित इंडेक्स। |

--------------------

1) PptxEditException को फेंकने से बचने के लिए पहले लेआउट की HasDependingSlides प्रॉपर्टी की जांच करें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) मेथड का भी उपयोग कर सकते हैं। 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

संग्रह से लेआउट स्लाइड को निर्दिष्ट स्थान पर ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य इंडेक्स। |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्थानांतरित करने के लिए स्लाइड। |