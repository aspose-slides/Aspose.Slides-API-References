---
title: AddBefore()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر را قبل از گره در فهرست اضافه می‌کند.
type: docs
weight: 66
url: /fa/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) متد

عنصر **element** را قبل از **node** در فهرست اضافه می‌کند.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node before which to insert |
| element | const T\& | Element to add |

### Return Value

گره جدید.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) متد

**newNode** را قبل از **node** در فهرست اضافه می‌کند.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node before which to insert |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | New node to add |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [LinkedListNode](../../linkedlistnode/)
* کلاس [LinkedList](../)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)