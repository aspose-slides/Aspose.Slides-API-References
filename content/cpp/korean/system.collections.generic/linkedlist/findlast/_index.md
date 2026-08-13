---
title: FindLast()
second_title: Aspose.Slides C++ API 레퍼런스
description: 리스트에서 요소를 역방향으로 찾습니다.
type: docs
weight: 170
url: /ko/system.collections.generic/linkedlist/findlast/
---
## LinkedList::FindLast(const T\&) const method

리스트에서 **element** 를 역방향으로 찾습니다.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::FindLast(const T &element) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | const T\& | 찾을 요소. |

### 반환 값

**element** 가 발견되면 해당 노드를 반환하고, 그렇지 않으면 nullptr 를 반환합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [LinkedListNode](../../linkedlistnode/)
* 클래스 [LinkedList](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)