---
title: Remove()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다/>
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) 메서드


컬렉션/>에서 특정 객체의 첫 번째 발생을 제거합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 컬렉션에서 제거할 객체. |

### 반환 값

*item* 이 컬렉션에서 성공적으로 제거되면 true; 그렇지 않으면 false. 원래 컬렉션에서 *item* 이 찾히지 않으면 이 메서드도 false를 반환합니다/>

## 비고



예: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)