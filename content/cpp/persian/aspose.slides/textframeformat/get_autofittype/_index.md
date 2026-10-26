---
title: get_AutofitType()
second_title: Aspose.Slides برای C++ مرجع API
description: حالت خودسازگاری متن را برمی‌گرداند. TextAutofitType را بخوانید.
type: docs
weight: 222
url: /fa/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() متد

حالت خودسازگاری متن را برمی‌گرداند. [TextAutofitType](../../textautofittype/) را بخوانید.

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## توضیحات

کد نمونه زیر نشان می‌دهد که چگونه شکل را برای Fit Text در یک PowerPoint [Presentation](../../presentation/) تغییر اندازه دهید.
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
کد نمونه زیر نشان می‌دهد که چگونه متن را در هنگام سرریز کوچک کنید.
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

## ملاحظات دیگر

* Enum [TextAutofitType](../../textautofittype/)
* کلاس [TextFrameFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)