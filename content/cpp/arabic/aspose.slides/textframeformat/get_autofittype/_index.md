---
title: get_AutofitType()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد وضعية ملاءمة النص تلقائيًا. اقرأ TextAutofitType.
type: docs
weight: 222
url: /ar/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() طريقة


يعيد وضعية ملاءمة النص تلقائيًا. اقرأ [TextAutofitType](../../textautofittype/).

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## ملاحظات


الشفرة العينية التالية توضح كيفية تغيير حجم الشكل لتناسب النص في PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
System::SharedPtr<ITextFrameFormat> textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_AutofitType(TextAutofitType::Shape);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```
 الشفرة العينية التالية توضح كيفية تصغير النص عند التدفق الزائد. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");

portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
System::SharedPtr<ITextFrameFormat> textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_AutofitType(TextAutofitType::Normal);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* Enum [TextAutofitType](../../textautofittype/)
* Class [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)