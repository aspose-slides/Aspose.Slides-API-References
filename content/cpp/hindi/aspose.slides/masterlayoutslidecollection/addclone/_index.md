---
title: AddClone()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) विधि


निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### वापसी मान

जोड़ी गई स्लाइड।

## टिप्पणियाँ



1) नया लेआउट इस लेआउट स्लाइड्स संग्रह के लिए पैरेंट मास्टर स्लाइड से जुड़ा होगा। इसलिए यह कॉपी/पेस्ट के समान है जिसमें PowerPoint में "Use Destination Theme" विकल्प होता है। 2) इस विधि का समकक्ष विधि [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) को [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) प्रॉपर्टी के साथ एक्सेस किया जाता है। 

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [MasterLayoutSlideCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)