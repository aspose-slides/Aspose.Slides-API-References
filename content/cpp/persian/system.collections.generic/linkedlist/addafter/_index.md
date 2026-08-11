---
title: AddAfter()
second_title: Aspose.Slides برای مرجع API C++
description: عنصری را پس از گره در لیست اضافه می‌کند.
type: docs
weight: 53
url: /fa/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) متد

عنصر **عنصر** را پس از **گره** در لیست اضافه می‌کند.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | گره‌ای که پس از آن درج می‌شود |
| element | const T\& | عنصری که باید اضافه شود |

### مقدار بازگشت

گره جدید.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) متد

گره جدید **گره جدید** را پس از **گره** در لیست اضافه می‌کند.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | گره‌ای که پس از آن درج می‌شود |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | گره جدید برای اضافه کردن |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)