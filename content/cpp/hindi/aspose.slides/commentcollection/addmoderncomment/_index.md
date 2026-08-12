---
title: AddModernComment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ें।
type: docs
weight: 66
url: /hi/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) मेथड


नई आधुनिक टिप्पणी को संग्रह के अंत में जोड़ें।

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | नई आधुनिक टिप्पणी का प्लेन टेक्स्ट। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) एक प्रस्तुति में जहाँ नई आधुनिक टिप्पणी जोड़नी है। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) एक स्लाइड पर जिससे नई आधुनिक टिप्पणी संबद्ध है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़नी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | आधुनिक टिप्पणी के निर्माण का समय। |

### रिटर्न वैल्यू

जोड़ी गई आधुनिक टिप्पणी।
## टिप्पणियाँ




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IModernComment](../../imoderncomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [IShape](../../ishape/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [CommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)