---
title: WeakPtr()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مؤشرًا فارغًا.
type: docs
weight: 1
url: /ar/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) منشئ

ينشئ مؤشرًا فارغًا.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) منشئ

ينشئ مؤشرًا ضعيفًا إلى الكائن المحدد.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) لإنشاء مؤشر ضعيف إلى. |

## WeakPtr::WeakPtr(const SmartPtr_&) منشئ

ينشئ مؤشرًا ضعيفًا يشير إلى نفس المؤشر الذي يشير إليه ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | المؤشر لنسخ قيمة العنصر المشار إليه من. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) منشئ

ينشئ مؤشرًا ضعيفًا يشير إلى نفس المؤشر الذي يشير إليه x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع العنصر المشار إليه للمؤشر المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | المؤشر لنسخ قيمة العنصر المشار إليه من. |

## WeakPtr::WeakPtr(const WeakPtr_&) منشئ

ينشئ نسخة من المؤشر الضعيف.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | المؤشر لنسخ قيمة العنصر المشار إليه من. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) منشئ

ينشئ نسخة من المؤشر الضعيف.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع العنصر المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | المؤشر لنسخ قيمة العنصر المشار إليه من. |

## WeakPtr::WeakPtr(SmartPtr_&&) منشئ

ينشئ المؤشر الضعيف بنقل.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | المؤشر لنقل قيمة العنصر المشار إليه من. |

## انظر أيضاً

* تعريف نوع [Pointee_](../../smartptr/pointee_/)
* تعريف نوع [SmartPtr_](../../smartptr/smartptr_/)
* تعريف نوع [WeakPtr_](../weakptr_/)
* فئة [WeakPtr](../)
* فئة [SmartPtr](../../smartptr/)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)