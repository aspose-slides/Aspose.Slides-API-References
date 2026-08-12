---
title: AddComment()
second_title: Aspose.Slides for C++ API संदर्भ
description: कलेक्शन के अंत में नई टिप्पणी जोड़ें।
type: docs
weight: 14
url: /hi/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) विधि

कलेक्शन के अंत में नई टिप्पणी जोड़ें।

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | नई टिप्पणी का सादे पाठ। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) प्रस्तुति में जहाँ नई टिप्पणी जोड़नी है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़नी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | टिप्पणी निर्माण का समय। |

### वापसी मान

जोडी गई टिप्पणी।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [ICommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)