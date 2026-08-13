---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 지정된 인덱스에 있는 항목을 제거합니다.
type: docs
weight: 157
url: /ko/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) 메서드

컬렉션에서 지정된 인덱스에 있는 항목을 제거합니다.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 항목의 0부터 시작하는 인덱스입니다. |
## 비고



예시: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## 참고

* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)