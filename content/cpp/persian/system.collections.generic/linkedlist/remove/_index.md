---
title: Remove()
second_title: Aspose.Slides برای C++ مرجع API
description: اولین رخداد عنصر مشخص شده را از لیست حذف می‌کند.
type: docs
weight: 196
url: /fa/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) متد

المان **element** را برای اولین بار از لیست حذف می‌کند.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| element | const T\& | element برای حذف. |

### مقدار بازگشت

True اگر **element** پیدا شد و حذف شد، false در غیر این صورت.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) متد

گره را از لیست حذف می‌کند.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | node برای حذف. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)