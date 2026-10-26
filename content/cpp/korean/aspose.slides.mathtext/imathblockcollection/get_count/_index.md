---
title: get_Count()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int32_t.
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() 메서드

컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## 비고

예: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## 참조

* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)