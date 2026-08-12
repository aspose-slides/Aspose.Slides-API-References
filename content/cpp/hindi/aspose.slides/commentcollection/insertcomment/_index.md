---
title: InsertComment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट अनुक्रमणिका पर एक संग्रह में नई टिप्पणी डालें।
type: docs
weight: 79
url: /hi/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) विधि

निर्दिष्ट अनुक्रमणिका पर संग्रह में नई टिप्पणी डालें।

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | एक संग्रह में उस तत्व का सूचकांक जहाँ टिप्पणी डाली जानी चाहिए। |
| text | [System::String](../../../system/string/) | नई टिप्पणी का साधारण पाठ। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) एक प्रस्तुति में जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | टिप्पणी निर्माण का समय। |

### रिटर्न वैल्यू

डाली गई टिप्पणी।

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [CommentCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)