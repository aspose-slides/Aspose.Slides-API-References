---
title: AddComment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंत में नई टिप्पणी जोड़ें।
type: docs
weight: 53
url: /hi/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) मेथड

संग्रह के अंत में नई टिप्पणी जोड़ें।

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | नई टिप्पणी का साधारण टेक्स्ट। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) प्रस्तुति में जहाँ नई टिप्पणी जोड़नी है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़नी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | टिप्पणी निर्माण का समय। |

### रिटर्न वैल्यू

जोड़ी गई टिप्पणी।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [CommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)