---
title: AddModernComment()
second_title: Aspose.Slides for C++ API संदर्भ
description: कलेक्शन के अंत में नई आधुनिक टिप्पणी जोड़ें।
type: docs
weight: 27
url: /hi/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

कलेक्शन के अंत में नई आधुनिक टिप्पणी जोड़ें।

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | नई आधुनिक टिप्पणी का सामान्य टेक्स्ट। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) वह प्रस्तुति जिसमें नया आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) स्लाइड पर जो नई आधुनिक टिप्पणी से जुड़ी है। |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | [System::DateTime](../../../system/datetime/) | आधुनिक टिप्पणी की निर्माण समय। |

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

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IModernComment](../../imoderncomment/)
* क्लास [String](../../../system/string/)
* क्लास [ISlide](../../islide/)
* क्लास [IShape](../../ishape/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [ICommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)