---
title: Insert()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에 컬렉션에 IMathBlock을(를) 삽입합니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) 메서드


지정된 인덱스에 컬렉션에 [IMathBlock](../../imathblock/)을(를) 삽입합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 항목을 삽입해야 하는 0 기반 인덱스. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 삽입할 [IMathBlock](../../imathblock/). |

## 비고

예제:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)