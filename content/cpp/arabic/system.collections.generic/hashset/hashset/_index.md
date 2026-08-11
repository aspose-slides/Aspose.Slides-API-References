---
title: HashSet()
second_title: Aspose.Slides لـ C++ مرجع API
description: معلومات RTTI.
type: docs
weight: 1
url: /ar/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor


RTTI information.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## ملاحظات


ينشئ مجموعة فارغة. 

## HashSet::HashSet(int) constructor


ينشئ مجموعة فارغة بسعة محددة.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor


ينشئ مجموعة فارغة تستخدم مُقارن المساواة المحدد.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```


### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) الكائن المرتبط بـ hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor


ينشئ hashset بناءً على قيم قابلة للتعداد.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [HashSet](../)
* فئة [IEqualityComparer](../../iequalitycomparer/)
* فئة [IEnumerable](../../ienumerable/)
* مساحة الاسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)