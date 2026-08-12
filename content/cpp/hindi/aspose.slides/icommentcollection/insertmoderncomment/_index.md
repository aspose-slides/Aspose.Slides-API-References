---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट इंडेक्स पर संग्रह में नई आधुनिक टिप्पणी सम्मिलित करें।
type: docs
weight: 53
url: /hi/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) विधि

निर्दिष्ट इंडेक्स पर संग्रह में नया आधुनिक टिप्पणी सम्मिलित करें।

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | उस संग्रह में तत्व का इंडेक्स जहाँ आधुनिक टिप्पणी सम्मिलित की जानी चाहिए। |
| text | [System::String](../../../system/string/) | नए आधुनिक टिप्पणी का साधारण टेक्स्ट। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) प्रेजेंटेशन में वह स्थान जहाँ नया आधुनिक टिप्पणी जोड़ा जाएगा। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) स्लाइड पर वह आकृति जिससे नया आधुनिक टिप्पणी जुड़ा है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थान जहाँ नया आधुनिक टिप्पणी जोड़ा जाना है। |
| creationTime | [System::DateTime](../../../system/datetime/) | आधुनिक टिप्पणी के निर्माण का समय। |

### रिटर्न वैल्यू

समावेशित आधुनिक टिप्पणी।

## देखें भी

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IModernComment](../../imoderncomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [IShape](../../ishape/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [ICommentCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)