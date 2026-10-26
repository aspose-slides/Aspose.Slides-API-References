---
title: get_WrapText()
second_title: Aspose.Slides for C++ API 참조
description: 텍스트가 TextFrame의 여백에서 자동 줄 바꿈되는 경우입니다. NullableBool을 읽으세요.
type: docs
weight: 118
url: /ko/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() 메서드


**True** 텍스트가 [TextFrame](../../textframe/)의 여백에서 자동 줄 바꿈되는 경우. [NullableBool](../../nullablebool/)을(를) 읽으세요.

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## 비고


다음 샘플 코드는 [Presentation](../../presentation/)에서 텍스트를 줄 바꿈하는 방법을 보여줍니다.
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

## 참고

* 열거형 [NullableBool](../../nullablebool/)
* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)