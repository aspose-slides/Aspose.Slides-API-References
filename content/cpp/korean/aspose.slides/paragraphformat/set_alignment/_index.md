---
title: set_Alignment()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 상속 없이 문단의 텍스트 정렬을 설정합니다. TextAlignment를 작성하십시오.
type: docs
weight: 14
url: /ko/aspose.slides/paragraphformat/set_alignment/
---
## ParagraphFormat::set_Alignment(TextAlignment) 메서드

문단에서 상속 없이 텍스트 정렬을 설정합니다. [TextAlignment](../../textalignment/)를 작성하십시오.

```cpp
void Aspose::Slides::ParagraphFormat::set_Alignment(TextAlignment value) override
```

## 비고

다음 예제 코드는 PowerPoint에서 텍스트 문단을 정렬하는 방법을 보여줍니다 [Presentation](../../presentation/).

```cpp
auto pres = System::MakeObject<Presentation>(u"ParagraphsAlignment.pptx");

// 첫 번째 슬라이드에 접근합니다
auto slide = pres->get_Slides()->idx_get(0);
// 슬라이드의 첫 번째와 두 번째 플레이스홀더에 접근하고 AutoShape으로 타입캐스팅합니다
System::SharedPtr<ITextFrame> tf1 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(0)))->get_TextFrame();
System::SharedPtr<ITextFrame> tf2 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(1)))->get_TextFrame();
// 두 플레이스홀더의 텍스트를 변경합니다
tf1->set_Text(u"Center Align by Aspose");
tf2->set_Text(u"Center Align by Aspose");
// 플레이스홀더의 첫 번째 문단을 가져옵니다
System::SharedPtr<IParagraph> para1 = tf1->get_Paragraphs()->idx_get(0);
System::SharedPtr<IParagraph> para2 = tf2->get_Paragraphs()->idx_get(0);
// 텍스트 문단을 가운데 정렬합니다
para1->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
para2->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
//프레젠테이션을 PPTX 파일로 저장합니다
pres->Save(u"Centeralign_out.pptx", SaveFormat::Pptx);
```

## 참고

* Enum [TextAlignment](../../textalignment/)
* 클래스 [ParagraphFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)