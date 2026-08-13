---
title: crbegin()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 반전된 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 반전되지 않은 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있는 경우, 반환된 반복자는 crend()와 같습니다.
type: docs
weight: 482
url: /ko/system/array/crbegin/
---
## Array::crbegin() const 메서드

반전된 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 반전되지 않은 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있는 경우, 반환된 반복자는 [crend()](../crend/)와 같습니다.

```cpp
const_reverse_iterator System::Array<T>::crbegin() const noexcept
```

### 반환 값

컨테이너의 마지막 const-한정 요소를 가리키는 반복자입니다.

## 참조

* 타입 정의 [const_reverse_iterator](../const_reverse_iterator/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)