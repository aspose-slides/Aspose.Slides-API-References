---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 객체를 ICollection에서 처음 발견되는 항목을 제거합니다.
type: docs
weight: 131
url: /ko/aspose.slides/portioncollection/remove/
---
## PortionCollection::Remove(System::SharedPtr\<IPortion\>) 메서드

특정 객체의 첫 번째 발생을 [ICollection](../../../system.collections.generic/icollection/)에서 제거합니다.

```cpp
bool Aspose::Slides::PortionCollection::Remove(System::SharedPtr<IPortion> item) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | [ICollection](../../../system.collections.generic/icollection/)에서 제거할 객체입니다. |

### 반환 값

*item*이 [ICollection](../../../system.collections.generic/icollection/)에서 성공적으로 제거되면 true; 그렇지 않으면 false. 이 메서드는 원래 [ICollection](../../../system.collections.generic/icollection/)에서 *item*을 찾을 수 없을 경우에도 false를 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortion](../../iportion/)
* 클래스 [PortionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)