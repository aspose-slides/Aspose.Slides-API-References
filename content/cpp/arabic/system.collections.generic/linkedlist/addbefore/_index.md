---
title: AddBefore()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف العنصر قبل العقدة في القائمة.
type: docs
weight: 66
url: /ar/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

يضيف **العنصر** قبل **العقدة** في القائمة.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة التي سيُدرج قبلها |
| element | const T\& | العنصر المراد إضافته |

### قيمة الإرجاع

العقدة الجديدة.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

يضيف **newNode** قبل **العقدة** في القائمة.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة التي سيُدرج قبلها |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة الجديدة التي ستُضاف |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)