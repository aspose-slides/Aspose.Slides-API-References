---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रेजेंटेशन में सभी लेआउट स्लाइड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/globallayoutslidecollection/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

प्रेजेंटेशन में सभी लेआउट स्लाइड्स के संग्रह का प्रतिनिधित्व करता है। LayoutSlideCollection क्लास को विस्तारित करता है जिसमें मास्टर के व्यक्तिगत लेआउट स्लाइड्स के संग्रहों को मिलाने के संदर्भ में लेआउट स्लाइड्स जोड़ने/क्लोन करने के लिए मेथड्स होते हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रेजेंटेशन में जोड़ता है। |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रेजेंटेशन में जोड़ता है। |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | प्रेजेंटेशन में एक नया लेआउट स्लाइड जोड़ता है। |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रेजेंटेशन में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रेजेंटेशनों के बीच लेआउट को क्लोन किया जाता है तो लेआउट का मास्टर भी स्रोत फॉर्मेटिंग को बनाए रखने के लिए क्लोन किया जा सकता है। आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर्स को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनाने से बचा जा सके। मास्टर स्लाइड्स का मैनुअल क्लोनिंग न तो रोका जाएगा न ही रजिस्टर्ड किया जाएगा। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ित स्लाइड।
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रेजेंटेशन में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड। |

--------------------

1) नया लेआउट गंतव्य प्रेजेंटेशन में परिभाषित मास्टर से जुड़ा होगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट का समतुल्य है। 2) इस मेथड का समकक्ष मेथड [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) प्रॉपर्टी के साथ एक्सेस किया जाता है। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ित स्लाइड।
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

प्रेजेंटेशन में एक नया लेआउट स्लाइड जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड। |
| layoutType | byte | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom। अन्य लेआउट प्रकार वर्तमान में समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject। |
| layoutName | java.lang.String | नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो पास किए गए लेआउट प्रकार के अनुसार नाम स्वतः उत्पन्न किया जाता है (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

1) layoutType के मूल्य SlideLayoutType.Custom के लिए जोड़ा गया लेआउट कोई प्लेसहोल्डर या शेप नहीं रखता है। 2) इस मेथड का समकक्ष मेथड [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) प्रॉपर्टी के साथ एक्सेस किया जाता है। 

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ित स्लाइड।