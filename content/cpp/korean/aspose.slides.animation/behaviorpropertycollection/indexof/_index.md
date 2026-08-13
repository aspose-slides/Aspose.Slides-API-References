---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IList에서 특정 항목의 인덱스를 결정합니다.
type: docs
weight: 40
url: /ko/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const 메서드

특정 항목의 인덱스를 [IList](../../../system.collections.generic/ilist/)에서 결정합니다.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [IList](../../../system.collections.generic/ilist/)에서 찾을 객체 |

### 반환 값

목록에서 찾은 경우 *item* 의 인덱스; 찾지 못한 경우 -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const 메서드

특정 항목을 속성 값으로 [IList](../../../system.collections.generic/ilist/)에서 인덱스를 결정합니다.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | 속성 값 |

### 반환 값

지정된 값을 가진 속성의 인덱스

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)