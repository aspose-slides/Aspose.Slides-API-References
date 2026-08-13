---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.
type: docs
weight: 170
url: /ko/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) 메서드


컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 요소의 0부터 시작하는 인덱스입니다. |
## 비고



예시: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## 관련 항목

* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)