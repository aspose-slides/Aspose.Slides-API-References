---
title: get_Alignment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속 없이 단락에서 텍스트 정렬을 반환합니다. TextAlignment를 읽어보세요.
type: docs
weight: 1
url: /ko/aspose.slides/paragraphformat/get_alignment/
---
## ParagraphFormat::get_Alignment() 메서드

텍스트 정렬을 상속 없이 단락에서 반환합니다. [TextAlignment](../../textalignment/)를 읽어보세요.

```cpp
TextAlignment Aspose::Slides::ParagraphFormat::get_Alignment() override
```

## 비고

다음 샘플 코드는 PowerPoint에서 텍스트 단락을 정렬하는 방법을 보여줍니다 [Presentation](../../presentation/).
```cpp
auto pres = System::MakeObject<Presentation>(u"ParagraphsAlignment.pptx");

// Accessing first slide
auto slide = pres->get_Slides()->idx_get(0);
// Accessing the first and second placeholder in the slide and typecasting it as AutoShape
System::SharedPtr<ITextFrame> tf1 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(0)))->get_TextFrame();
System::SharedPtr<ITextFrame> tf2 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(1)))->get_TextFrame();
// Change the text in both placeholders
tf1->set_Text(u"Center Align by Aspose");
tf2->set_Text(u"Center Align by Aspose");
// Getting the first paragraph of the placeholders
System::SharedPtr<IParagraph> para1 = tf1->get_Paragraphs()->idx_get(0);
System::SharedPtr<IParagraph> para2 = tf2->get_Paragraphs()->idx_get(0);
// Aligning the text paragraph to center
para1->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
para2->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
//Writing the presentation as a PPTX file
pres->Save(u"Centeralign_out.pptx", SaveFormat::Pptx);
```

## 참고

* 열거형 [TextAlignment](../../textalignment/)
* 클래스 [ParagraphFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)