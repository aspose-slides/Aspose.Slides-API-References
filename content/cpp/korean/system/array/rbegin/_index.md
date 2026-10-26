---
title: rbegin()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 반전된 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 비반전 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있는 경우 반환된 반복자는 rend()와 같습니다.
type: docs
weight: 469
url: /ko/system/array/rbegin/
---
## Array::rbegin() 메서드

반전된 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 비반전 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있는 경우 반환된 반복자는 [rend()](../rend/)와 같습니다.

```cpp
reverse_iterator System::Array<T>::rbegin() noexcept
```

### 반환값

컨테이너의 마지막 요소를 가리키는 반복자.

## Array::rbegin() const 메서드

반전된 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 비반전 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있는 경우 반환된 반복자는 [rend()](../rend/)와 같습니다.

```cpp
const_reverse_iterator System::Array<T>::rbegin() const noexcept
```

### 반환값

const 한정된 컨테이너의 마지막 요소를 가리키는 반복자.

## 참고

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)