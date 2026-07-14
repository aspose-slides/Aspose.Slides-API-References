---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: प्रस्तुति में सभी लेआउट स्लाइड्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/igloballayoutslidecollection/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

प्रस्तुति में सभी लेआउट स्लाइड्स का एक संग्रह दर्शाता है। ILayoutSlideCollection इंटरफ़ेस को उन तरीकों के साथ विस्तारित करता है जो व्यक्तिगत मास्टर लेआउट स्लाइड्स के संग्रह को मिलाने के संदर्भ में लेआउट स्लाइड्स को जोड़ने/क्लोन करने के लिए हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है। |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है। |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | प्रस्तुति में एक नया लेआउट स्लाइड जोड़ता है। |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड।

--------------------

विभिन्न प्रस्तुतियों के बीच लेआउट क्लोन करते समय लेआउट की मास्टर को भी क्लोन किया जा सकता है ताकि स्रोत स्वरूपण बना रहे। आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर्स को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनना न पड़े। मास्टर स्लाइड्स की मैन्युअल क्लोनिंग न तो रोकी जाती है न ही पंजीकृत की जाती है। |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

निर्दिष्ट लेआउट स्लाइड की एक प्रति प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड।

--------------------

नया लेआउट गंतव्य प्रस्तुति में परिभाषित मास्टर के साथ जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

नया लेआउट स्लाइड प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | नए लेआउट के लिए मास्टर स्लाइड। |
| layoutType | byte | नए लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नए लेआउट का नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException उत्पन्न होगी। यदि null पास किया जाता है तो पास किए गए लेआउट प्रकार के अनुसार नाम स्वचालित रूप से उत्पन्न होगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)।

--------------------

1) layoutType के मान SlideLayoutType.Custom के लिए जोड़ा गया लेआउट कोई प्लेसहोल्डर और कोई आकार नहीं रखता है। 2) इस मेथड का समकक्ष मेथड [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) प्रॉपर्टी के साथ पहुंचा जाता है। |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।