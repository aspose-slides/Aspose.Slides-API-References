---
title: get_AutofitType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트의 자동 맞춤 모드를 반환합니다. TextAutofitType을(를) 읽으세요.
type: docs
weight: 222
url: /ko/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() 메서드


텍스트의 자동 맞춤 모드를 반환합니다. [TextAutofitType](../../textautofittype/)을(를) 읽으세요.

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## 비고


다음 샘플 코드는 PowerPoint [Presentation](../../presentation/)에서 텍스트에 맞추도록 도형 크기를 조정하는 방법을 보여줍니다. 
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
 다음 샘플 코드는 텍스트가 넘칠 때 텍스트를 축소하는 방법을 보여줍니다. 
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

## 참조

* Enum [TextAutofitType](../../textautofittype/)
* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)