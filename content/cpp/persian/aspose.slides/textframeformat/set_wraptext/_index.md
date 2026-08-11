---
title: set_WrapText()
second_title: Aspose.Slides برای C++ مرجع API
description: True اگر متن در حاشیه‌های TextFrame بسته شود. نوشتن NullableBool.
type: docs
weight: 131
url: /fa/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) متد

**True** اگر متن در حاشیه‌های [TextFrame](../../textframe/)'s بسته شود. بنویسید [NullableBool](../../nullablebool/).

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه می‌توان متن را در [Presentation](../../presentation/) بسته.

```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
auto textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_WrapText(NullableBool::True);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Enum [NullableBool](../../nullablebool/)
* کلاس [TextFrameFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)