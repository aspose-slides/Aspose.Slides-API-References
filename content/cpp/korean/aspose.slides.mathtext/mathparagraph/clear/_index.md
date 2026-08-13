---
title: Clear()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 모든 요소를 제거합니다.
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() 메서드


컬렉션에서 모든 요소를 제거합니다.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## 비고


예제:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## 참고

* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)