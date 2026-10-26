---
title: idx_get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 있는 항목을 가져옵니다. 읽기 전용 IMathBlock.
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) 메서드

지정된 인덱스에 있는 항목을 가져옵니다. 읽기 전용 [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 가져올 항목의 0부터 시작하는 인덱스 |

### 반환값

수학 텍스트 블록.

## 비고

예시:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)