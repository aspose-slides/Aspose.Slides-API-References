---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रेज़ेंटेशन में सभी लेआउट स्लाइडों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/globallayoutslidecollection/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

प्रेज़ेंटेशन में सभी लेआउट स्लाइडों का एक संग्रह दर्शाता है। LayoutSlideCollection क्लास को विस्तारित करता है जिसमें व्यक्तिगत मास्टर लेआउट स्लाइडों के संग्रह को मिलाने के संदर्भ में लेआउट स्लाइड जोड़ने/क्लोन करने के लिए विधियाँ हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | प्रेज़ेंटेशन में एक निर्दिष्ट लेआउट स्लाइड की प्रति जोड़ता है। |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | प्रेज़ेंटेशन में एक निर्दिष्ट लेआउट स्लाइड की प्रति जोड़ता है। |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | प्रेज़ेंटेशन में एक नई लेआउट स्लाइड जोड़ता है। |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


प्रेज़ेंटेशन में एक निर्दिष्ट लेआउट स्लाइड की प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच लेआउट क्लोन किया जाता है, तो लेआउट का मास्टर भी स्रोत फ़ॉर्मेट को बनाए रखने के लिए क्लोन किया जा सकता है। स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए आंतरिक रजिस्ट्री का उपयोग किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से बचा जा सके। मास्टर स्लाइड के मैनुअल क्लोनिंग को न तो रोका जाएगा न ही रजिस्टर किया जाएगा। 

**परिणाम:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


प्रेज़ेंटेशन में एक निर्दिष्ट लेआउट स्लाइड की प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई लेआउट के लिए मास्टर स्लाइड। |

--------------------

1) नई लेआउट गंतव्य प्रस्तुति में परिभाषित मास्टर से जुड़ी होगी। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समकक्ष है। 2) इस विधि का समकक्ष विधि [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) है जिसे ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) प्रॉपर्टी के साथ एक्सेस किया जाता है। 

**परिणाम:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


नई लेआउट स्लाइड को प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई लेआउट के लिए मास्टर स्लाइड। |
| layoutType | byte | नई लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नई लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException उत्पन्न होगा। यदि null पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से पास किए गए लेआउट प्रकार के आधार पर उत्पन्न किया जाएगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

1) layoutType के मान SlideLayoutType.Custom के लिए जोड़ी गई लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं होता है। 2) इस विधि का समकक्ष विधि [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) है जिसे ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) प्रॉपर्टी के साथ एक्सेस किया जाता है। 

**परिणाम:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।