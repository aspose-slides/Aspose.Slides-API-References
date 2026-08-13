---
title: Contains()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에 특정 값이 포함되어 있는지 확인합니다.
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) 메서드


컬렉션에 특정 값이 포함되어 있는지 확인합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 컬렉션에서 찾을 객체. |

### 반환 값

*item*이(가) 컬렉션에서 발견되면 true; 그렇지 않으면 false.
## 비고



예: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathBlockCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)