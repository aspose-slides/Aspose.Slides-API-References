---
title: InsertComment()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट इंडेक्स पर संग्रह में नई टिप्पणी डालें।
type: docs
weight: 40
url: /hi/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

निर्दिष्ट इंडेक्स पर संग्रह में नई टिप्पणी डाली जाती है।

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | संग्रह में वह तत्व का इंडेक्स जहाँ टिप्पणी डाली जानी चाहिए। |
| text | [System::String](../../../system/string/) | नई टिप्पणी का साधारण पाठ। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) प्रस्तुति में जहाँ नई टिप्पणी जोड़नी है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थान जहाँ नई टिप्पणी जोड़नी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | टिप्पणी निर्माण का समय। |

### रिटर्न मान

डाली गई टिप्पणी।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [ICommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)