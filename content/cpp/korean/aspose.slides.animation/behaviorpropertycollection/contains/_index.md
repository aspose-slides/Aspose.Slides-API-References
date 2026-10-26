---
title: Contains()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ICollection에 특정 값이 포함되어 있는지 확인합니다.
type: docs
weight: 118
url: /ko/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const 메서드


[ICollection](../../../system.collections.generic/icollection/)에 특정 값이 포함되어 있는지 확인합니다.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [ICollection](../../../system.collections.generic/icollection/)에서 찾을 속성입니다. |

### 반환 값

[ICollection](../../../system.collections.generic/icollection/)에서 *item*을(를) 찾으면 true, 그렇지 않으면 false.

## BehaviorPropertyCollection::Contains(const System::String\&) const 메서드


[ICollection](../../../system.collections.generic/icollection/)에 특정 값이 포함되어 있는지 확인합니다.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | [ICollection](../../../system.collections.generic/icollection/)에서 찾을 속성 값입니다. |

### 반환 값

[ICollection](../../../system.collections.generic/icollection/)에서 *propertyValue*을(를) 찾으면 true, 그렇지 않으면 false.

## 기타 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBehaviorProperty](../../ibehaviorproperty/)
* 클래스 [BehaviorPropertyCollection](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)