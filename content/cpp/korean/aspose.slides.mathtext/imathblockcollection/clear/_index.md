---
title: Clear()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션의 모든 요소를 제거합니다.
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() 메서드

컬렉션에서 모든 요소를 제거합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## 비고

예시:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## 참조

* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)