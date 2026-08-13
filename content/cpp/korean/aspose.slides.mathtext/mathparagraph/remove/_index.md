---
title: Remove()
second_title: Aspose.Slides C++ API 레퍼런스
description: 컬렉션에서 특정 객체의 첫 번째 항목을 제거합니다/>
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) 메서드

컬렉션에서 특정 객체의 첫 번째 항목을 제거합니다/>

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 컬렉션에서 제거할 객체. |

### 반환 값

컬렉션에서 *mathBlock*  가 성공적으로 제거되면 true; 그렇지 않으면 false. 원래 컬렉션에서 *mathBlock*  를 찾을 수 없는 경우에도 이 메서드는 false를 반환합니다/>

## 비고



예: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## 참고

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)