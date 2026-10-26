---
title: AddAfter()
second_title: Aspose.Slides for C++ API 참조
description: 목록의 노드 뒤에 요소를 추가합니다.
type: docs
weight: 53
url: /ko/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) 메서드

목록의 **node** 뒤에 **element**를 추가합니다.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 삽입할 노드 |
| element | const T\& | 추가할 요소 |

### 반환값

새 노드.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) 메서드

목록의 **node** 뒤에 **newNode**를 추가합니다.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 삽입할 노드 |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 추가할 새 노드 |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [LinkedListNode](../../linkedlistnode/)
* 클래스 [LinkedList](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)