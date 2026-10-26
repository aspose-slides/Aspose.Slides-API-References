---
title: AddFirst()
second_title: Aspose.Slides for C++ API 참조
description: 리스트의 시작에 요소를 추가합니다.
type: docs
weight: 79
url: /ko/system.collections.generic/linkedlist/addfirst/
---
## LinkedList::AddFirst(const T\&) 메서드

리스트의 시작에 **element**을(를) 추가합니다.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddFirst(const T &element)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | const T\& | 추가할 element. |

### 반환 값

새 노드.

## LinkedList::AddFirst(const SharedPtr\<LinkedListNode\<T\>\>\&) 메서드

리스트의 시작에 **newNode**을(를) 추가합니다.

```cpp
void System::Collections::Generic::LinkedList<T>::AddFirst(const SharedPtr<LinkedListNode<T>> &newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 추가할 새 노드. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [LinkedListNode](../../linkedlistnode/)
* 클래스 [LinkedList](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)