---
title: IndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 특정 IMathBlock의 인덱스를 결정합니다.
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) 메서드

컬렉션에서 특정 [IMathBlock](../../imathblock/)의 인덱스를 결정합니다.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 컬렉션에서 찾을 항목입니다. |

## 반환값

컬렉션에서 찾은 경우 *item*의 인덱스; 찾지 못하면 -1.

## 비고



예시: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)