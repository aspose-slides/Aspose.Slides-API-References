---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रस्तुति में सभी लेआउट स्लाइड्स का संग्रह प्रस्तुत करता है।
type: docs
url: /hi/com.aspose.slides/igloballayoutslidecollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

प्रस्तुति में सभी लेआउट स्लाइड्स का संग्रह प्रस्तुत करता है। ILayoutSlideCollection इंटरफ़ेस को विस्तारित करता है जिसमें व्यक्तिगत मास्टर की लेआउट स्लाइड्स के संग्रह को एकीकृत करने के संदर्भ में लेआउट स्लाइड्स जोड़ने/क्लोन करने की विधियाँ होती हैं।

## विधियां

| विधि | विवरण |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | प्रस्तुति में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है। |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | प्रस्तुति में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है। |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | प्रस्तुति में एक नई लेआउट स्लाइड जोड़ता है। |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

प्रस्तुति में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |

--------------------

जब विभिन्न प्रस्तुतियों के बीच लेआउट को क्लोन किया जाता है, लेआउट का मास्टर भी स्रोत फॉर्मेटिंग को बनाए रखने के लिए क्लोन किया जा सकता है। एक आंतरिक रजिस्ट्री का उपयोग स्वचालित रूप से क्लोन किए गए मास्टर को ट्रैक करने के लिए किया जाता है ताकि समान मास्टर स्लाइड के कई क्लोन बनना न पड़े। मास्टर स्लाइड्स की मैन्युअल क्लोनिंग न तो रोकी जाएगी और न ही रजिस्टर्ड होगी।

**वापसी मान:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

प्रस्तुति में निर्दिष्ट लेआउट स्लाइड की एक प्रति जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | क्लोन करने के लिए स्लाइड। |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई लेआउट के लिए मास्टर स्लाइड। |

--------------------

नया लेआउट गंतव्य प्रस्तुति में निर्धारित मास्टर से जुड़ जाएगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के बराबर है।

**वापसी मान:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

प्रस्तुति में एक नई लेआउट स्लाइड जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | नई लेआउट के लिए मास्टर स्लाइड। |
| layoutType | byte | नई लेआउट के लिए लेआउट प्रकार। समर्थित लेआउट प्रकार: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. अन्य लेआउट प्रकार अभी समर्थित नहीं हैं: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | नई लेआउट के लिए नाम। यदि दिया गया नाम पहले से उपयोग में है तो ArgumentException फेंका जाएगा। यदि null पैरामीटर पास किया जाता है तो नाम स्वचालित रूप से दिया गया लेआउट प्रकार के अनुसार उत्पन्न किया जाएगा (उदाहरण के लिए "Title Slide" या "1_Title Slide", "2_..", आदि)। |

--------------------

1) layoutType के SlideLayoutType.Custom मान के लिए जोड़ा गया लेआउट में कोई प्लेसहोल्डर और कोई आकार नहीं होता। 2) इस विधि का समानांतर विधि [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) प्रॉपर्टी के साथ पहुँचा जाता है।

**वापसी मान:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - जोड़ी गई स्लाइड।