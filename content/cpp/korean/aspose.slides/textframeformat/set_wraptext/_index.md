---
title: set_WrapText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: True이면 텍스트가 TextFrame의 여백에서 줄바꿈됩니다. NullableBool을 작성하십시오.
type: docs
weight: 131
url: /ko/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) 메서드

**True** [TextFrame](../../textframe/)의 여백에서 텍스트가 줄바꿈됩니다. [NullableBool](../../nullablebool/)을 작성하십시오.

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## 비고

다음 샘플 코드는 [Presentation](../../presentation/)에서 텍스트를 줄바꿈하는 방법을 보여줍니다.

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

## 관련 항목

* Enum [NullableBool](../../nullablebool/)
* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)