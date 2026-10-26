---
title: crend()
second_title: Aspose.Slides for C++ API 참조
description: 역전된 컨테이너에서 마지막 요소 뒤에 있는 요소에 대한 역방향 반복자를 반환합니다. 이는 비역전된 컨테이너의 첫 번째 요소 앞에 있는 요소에 해당합니다. 이 요소는 자리표시자 역할을 하며, 접근을 시도하면 정의되지 않은 동작이 발생합니다.
type: docs
weight: 300
url: /ko/system.collections.specialized/stringcollection/crend/
---
## StringCollection::crend() const 메서드

역방향 반복자를 반환합니다. 역전된 컨테이너에서 마지막 요소 뒤에 있는 요소를 가리킵니다. 이는 비역전된 컨테이너의 첫 번째 요소 앞에 있는 요소에 해당합니다. 이 요소는 자리표시자 역할을 하며, 접근을 시도하면 정의되지 않은 동작이 발생합니다.

```cpp
const_reverse_iterator System::Collections::Specialized::StringCollection::crend() const noexcept
```

### 반환값

컨테이너의 첫 번째 요소 앞에 있는 이론적인 const 한정 요소를 가리키는 반복자입니다.

## 참조

* 타입정의 [const_reverse_iterator](../const_reverse_iterator/)
* 클래스 [StringCollection](../)
* 네임스페이스 [System::Collections::Specialized](../../)
* 라이브러리 [Aspose.Slides](../../../)