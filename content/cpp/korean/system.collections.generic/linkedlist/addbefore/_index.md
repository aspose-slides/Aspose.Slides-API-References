---
title: AddBefore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 리스트의 노드 앞에 요소를 추가합니다.
type: docs
weight: 66
url: /ko/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

리스트의 **node** 앞에 **element**를 추가합니다.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node before which to insert |
| element | const T\& | Element to add |

### 반환값

새 노드.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

리스트의 **node** 앞에 **newNode**를 추가합니다.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node before which to insert |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | New node to add |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [LinkedListNode](../../linkedlistnode/)
* 클래스 [LinkedList](../)
* 네임스페이스 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)