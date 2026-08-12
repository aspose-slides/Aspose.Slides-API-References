---
title: AddClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

किसी निर्दिष्ट लेआउट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### Return Value

जोड़ी गई स्लाइड।

## Remarks

1) नया लेआउट इस लेआउट स्लाइड्स संग्रह के लिए मूल मास्टर स्लाइड से जुड़ा रहेगा। इसलिए यह PowerPoint में "Use Destination Theme" विकल्प के साथ कॉपी/पेस्ट के समान है। 2) इस विधि का समकक्ष विधि [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) है जिसे [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) प्रॉपर्टी के माध्यम से एक्सेस किया जाता है। 

## See Also

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ILayoutSlide](../../ilayoutslide/)
* क्लास [IMasterLayoutSlideCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)