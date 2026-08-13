---
title: Remove()
second_title: C++용 Aspose.Slides API 참조
description: 목록에서 지정된 요소를 처음으로 발견하여 제거합니다.
type: docs
weight: 196
url: /ko/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) method

리스트에서 지정된 **element** 를 처음으로 발견하여 제거합니다.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | const T\& | 제거할 요소. |

### 반환 값

**element** 가 찾아져서 제거되면 true, 그렇지 않으면 false.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) method

리스트에서 노드를 제거합니다.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 제거할 node. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)