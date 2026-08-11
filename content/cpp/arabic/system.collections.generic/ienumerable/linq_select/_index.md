---
title: LINQ_Select()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل عناصر تسلسل.
type: docs
weight: 248
url: /ar/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) طريقة

يحوّل عناصر تسلسل.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| ResultType | نوع القيمة التي تُرجعها **selector**. |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | دالة تحويل. |

### قيمة الإرجاع

‏[IEnumerable](../) يحتوي على العناصر التي تُرجعها دالة **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) طريقة

يحوّل كل عنصر من تسلسل إلى شكل جديد عن طريق تضمين فهرس العنصر.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| ResultType | نوع القيمة التي تُرجعها **selector**. |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | دالة تحويل. |

### قيمة الإرجاع

‏[IEnumerable](../) يحتوي على العناصر التي تُرجعها دالة **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) طريقة




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) طريقة




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IEnumerable](../)
* فئة [Func](../../../system/func/)
* نطاق [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)