---
title: AddLast()
second_title: C++용 Aspose.Slides API 참조
description: 요소를 리스트의 끝에 추가합니다.
type: docs
weight: 92
url: /ko/system.collections.generic/linkedlist/addlast/
---
## LinkedList::AddLast(const T\&) 메서드

리스트의 끝에 **element**를 추가합니다.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddLast(const T &element)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | const T\& | 추가할 요소. |

### 반환값

새 노드.

## LinkedList::AddLast(const SharedPtr\<LinkedListNode\<T\>\>\&) 메서드

리스트의 끝에 **newNode**을 추가합니다.

```cpp
void System::Collections::Generic::LinkedList<T>::AddLast(const SharedPtr<LinkedListNode<T>> &newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 추가할 새 노드. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [LinkedListNode](../../linkedlistnode/)
* 클래스 [LinkedList](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)