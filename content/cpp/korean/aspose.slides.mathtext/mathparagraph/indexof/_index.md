---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 특정 IMathBlock의 인덱스를 결정합니다.
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) 메서드

컬렉션에서 특정 [IMathBlock](../../imathblock/)의 인덱스를 결정합니다.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 컬렉션에서 찾을 항목입니다. |

### 반환 값

컬렉션에서 찾은 경우 *mathBlock*의 인덱스; 그렇지 않으면 -1.

## 비고

```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)