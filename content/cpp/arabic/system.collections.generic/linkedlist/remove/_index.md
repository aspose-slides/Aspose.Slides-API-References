---
title: Remove()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل أول ظهور للعنصر المحدد من القائمة.
type: docs
weight: 196
url: /ar/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) method


يزيل أول ظهور للـ **element** المحدد من القائمة.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| element | const T\& | العنصر المراد إزالته. |

### قيمة الإرجاع

True إذا تم العثور على **element** وإزالته، false وإلا.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) method


يزيل العقدة من القائمة.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | العقدة المراد إزالتها. |

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)