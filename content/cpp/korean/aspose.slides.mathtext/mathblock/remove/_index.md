---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) 메서드


컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 컬렉션에서 제거할 객체입니다. |

### 반환값

true if *item*  was successfully removed from the collection; otherwise, false. This method also returns false if *item*  is not found in the original collection.

## 비고



예시: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)