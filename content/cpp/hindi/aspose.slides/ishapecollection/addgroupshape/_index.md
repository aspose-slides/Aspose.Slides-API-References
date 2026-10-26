---
title: AddGroupShape()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया खाली समूह शैप बनाता है और इसे शैप संग्रह के अंत में जोड़ता है। समूह\\u2019s फ्रेम स्वचालित रूप से जोड़े गए किसी भी शैप को फिट करने के लिए समायोजित हो जाएगा।
type: docs
weight: 352
url: /hi/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() विधि

एक नया खाली समूह शैप बनाता है और इसे शैप संग्रह के अंत में जोड़ता है। समूह\u2019s फ्रेम स्वचालित रूप से जोड़े गए किसी भी शैप को फिट करने के लिए समायोजित हो जाएगा।

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### वापसी मान

नया बनाया गया [IGroupShape](../../igroupshape/)।

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) विधि

एक नया समूह शैप बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत शैप में परिवर्तित करता है, और परिणामी समूह को शैप संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | वेक्टर सामग्री को शैप में बदलने वाली [ISvgImage](../../isvgimage/)। |
| x | **float** | समूह\u2019s फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | समूह\u2019s फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | समूह\u2019s फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | समूह\u2019s फ्रेम की ऊँचाई, पॉइंट्स में। |

### वापसी मान

नया बनाया गया [IGroupShape](../../igroupshape/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IGroupShape](../../igroupshape/)
* क्लास [IShapeCollection](../)
* क्लास [ISvgImage](../../isvgimage/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)