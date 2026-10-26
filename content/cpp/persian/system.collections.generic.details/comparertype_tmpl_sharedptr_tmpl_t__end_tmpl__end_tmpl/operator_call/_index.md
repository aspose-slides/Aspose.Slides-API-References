---
title: operator()()
second_title: Aspose.Slides برای C++ مرجع API
description: انواع اشاره‌گر را که رابط IComparable را پیاده‌سازی می‌کنند، مقایسه می‌کند.
type: docs
weight: 1
url: /fa/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const متد

مقایسه می‌کند انواع اشاره‌گر که [IComparable](../../../system/icomparable/) رابط را پیاده‌سازی می‌کنند.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | مقدار سمت چپ. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | مقدار سمت راست. |

### مقدار بازگشتی

True اگر **a** کمتر از **b** در نظر گرفته شود؛ در غیر این صورت false.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const متد

مقایسه می‌کند انواع اشاره‌گری که [IComparable](../../../system/icomparable/) رابط را پیاده‌سازی نمی‌کنند.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | مقدار سمت چپ. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | مقدار سمت راست. |

### مقدار بازگشتی

True اگر **a** کمتر از **b** در نظر گرفته شود؛ در غیر این صورت false.

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IComparable](../../../system/icomparable/)
* ساختار [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* ساختار [ComparerType< SharedPtr< T > >](../)
* فضای‌نام [System::Collections::Generic::Details](../../)
* کتابخانه [Aspose.Slides](../../../)