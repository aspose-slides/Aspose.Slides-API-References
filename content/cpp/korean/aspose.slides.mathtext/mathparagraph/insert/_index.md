---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 컬렉션에 IMathBlock을 삽입합니다.
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) 메서드

지정된 인덱스에 컬렉션에 [IMathBlock](../../imathblock/)을 삽입합니다.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 삽입할 항목이 위치할 0부터 시작하는 인덱스입니다. |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 삽입할 [IMathBlock](../../imathblock/). |
## 비고



예제: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)