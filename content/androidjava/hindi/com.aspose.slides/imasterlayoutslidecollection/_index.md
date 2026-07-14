---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: परिभाषित मुख्य स्लाइड के सभी लेआउट स्लाइड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imasterlayoutslidecollection/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

परिभाषित मुख्य स्लाइड के सभी लेआउट स्लाइड्स का संग्रह दर्शाता है। ILayoutSlideCollection इंटरफ़ेस का विस्तार करता है जिसमें लेआउट स्लाइड्स को जोड़ने/डालने/हटाने/क्लोन करने के लिए विधियाँ शामिल हैं, जो मुख्य स्लाइड की व्यक्तिगत लेआउट स्लाइड्स संग्रह के संदर्भ में हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | किसी निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | किसी निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थान पर डालता है। |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | एक नया लेआउट स्लाइड संग्रह के अंत में जोड़ता है। |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | एक नया लेआउट स्लाइड संग्रह में निर्दिष्ट स्थान पर डालता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर स्थित तत्व को हटाता है। |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | लेआउट स्लाइड को संग्रह से निकालकर निर्दिष्ट स्थान पर ले जाता है। |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

किसी निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिये स्लाइड। |
--------------------
1) नया लेआउट इस लेआउट स्लाइड्स संग्रह के मूल मुख्य स्लाइड से जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 2) इस विधि का समकक्ष विधि [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) है जिसे [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है।

**वापसी मान:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

किसी निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थान पर डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमांक। |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिये स्लाइड। |
--------------------
नया लेआउट इस लेआउट स्लाइड्स संग्रह के मूल मुख्य स्लाइड से जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है।

**वापसी मान:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - डाली गई स्लाइड।

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

एक नया लेआउट स्लाइड संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layoutType | byte | नए लेआउट के लिये लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार अभी समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नए लेआउट के लिये नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException उछाला जाएगा। यदि null पैरामीटर दिया जाता है तो लेआउट प्रकार के अनुसार नाम स्वतः उत्पन्न किया जाएगा (उदाहरण के लिये "Title Slide" या "1_Title Slide", "2_.." आदि)। |
--------------------
1) layoutType के मान SlideLayoutType.Custom के लिये जोड़ी गई लेआउट में कोई प्लेसहोल्डर और कोई आकृतियाँ नहीं होतीं। 2) इस विधि का समकक्ष विधि [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) है जिसे [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है।

**वापसी मान:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

एक नया लेआउट स्लाइड संग्रह में निर्दिष्ट स्थान पर डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए स्लाइड का अनुक्रमांक। |
| layoutType | byte | नए लेआउट के लिये लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार अभी समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नए लेआउट के लिये नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException उछाला जाएगा। यदि null पैरामीटर दिया जाता है तो लेआउट प्रकार के अनुसार नाम स्वतः उत्पन्न किया जाएगा (उदाहरण के लिये "Title Slide" या "1_Title Slide", "2_.." आदि)। |
--------------------
layoutType के मान SlideLayoutType.Custom के लिये डाली गई लेआउट में कोई प्लेसहोल्डर और कोई आकृतियाँ नहीं होतीं।

**वापसी मान:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - डाली गई स्लाइड।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर स्थित तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |
--------------------
1) PptxEditException के फेंके जाने से बचने के लिये लेआउट की HasDependingSlides प्रॉपर्टी को पहले जाँचें। 2) आप कोड को सरल बनाने के लिये [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) विधि का भी उपयोग कर सकते हैं।

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

लेआउट स्लाइड को संग्रह से निकालकर निर्दिष्ट स्थान पर ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य अनुक्रमांक। |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | स्थानांतरित करने के लिये स्लाइड। |