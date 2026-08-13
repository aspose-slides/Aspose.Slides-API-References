---
title: Contains()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 특정 값이 포함되어 있는지 확인합니다.
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) 메서드


컬렉션에 특정 값이 포함되어 있는지 확인합니다.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 컬렉션에서 찾을 객체입니다. |

### 반환값

컬렉션에서 *mathBlock*을 찾으면 true; 그렇지 않으면 false.
## 비고



예: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)