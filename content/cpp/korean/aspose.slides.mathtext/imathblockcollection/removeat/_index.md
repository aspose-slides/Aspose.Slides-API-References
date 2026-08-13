---
title: RemoveAt()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 컬렉션에서 지정된 인덱스에 있는 항목을 제거합니다.
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) 메서드

컬렉션에서 지정된 인덱스에 있는 항목을 제거합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 항목의 0부터 시작하는 인덱스입니다. |
## 비고



예제: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## 관련 항목

* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)