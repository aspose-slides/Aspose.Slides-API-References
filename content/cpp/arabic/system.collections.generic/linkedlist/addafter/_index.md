---
title: AddAfter()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف العنصر بعد العقدة في القائمة.
type: docs
weight: 53
url: /ar/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) طريقة

يضيف **element** بعد **node** من القائمة.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة التي سيتم الإدراج بعدها |
| element | const T\& | العنصر المراد إضافته |

### قيمة الإرجاع

العقدة الجديدة.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) طريقة

يضيف **newNode** بعد **node** من القائمة.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة التي سيتم الإدراج بعدها |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة الجديدة التي سيتم إضافتها |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [LinkedListNode](../../linkedlistnode/)
* فئة [LinkedList](../)
* نطاق [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)