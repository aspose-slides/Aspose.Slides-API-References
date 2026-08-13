---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) 메서드

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 요소의 0부터 시작하는 인덱스입니다. |
## 비고



예시: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## 참고

* 클래스 [IMathElementCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)