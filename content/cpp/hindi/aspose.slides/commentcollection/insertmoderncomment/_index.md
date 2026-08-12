---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट इंडेक्स पर संग्रह में नई आधुनिक टिप्पणी डालें।
type: docs
weight: 92
url: /hi/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) मेथड

निर्दिष्ट इंडेक्स पर संग्रह में नई आधुनिक टिप्पणी डालें।

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | संग्रह में उस तत्व का इंडेक्स जहाँ आधुनिक टिप्पणी डालनी है। |
| text | [System::String](../../../system/string/) | नए आधुनिक टिप्पणी का साधारण पाठ। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) एक प्रस्तुतीकरण में जहाँ नई आधुनिक टिप्पणी जोड़नी है। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) स्लाइड पर जिससे नई आधुनिक टिप्पणी जुड़ी है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़नी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | आधुनिक टिप्पणी निर्माण का समय। |

### रिटर्न मान

डाली गई आधुनिक टिप्पणी।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IModernComment](../../imoderncomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [IShape](../../ishape/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [CommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)