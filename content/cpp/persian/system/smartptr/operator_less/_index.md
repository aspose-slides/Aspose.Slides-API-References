---
title: operator<()
second_title: Aspose.Slides برای C++ مرجع API
description: معنای مقایسه کمتر را برای کلاس SmartPtr فراهم می‌کند.
type: docs
weight: 235
url: /fa/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const متد


معنای مقایسه کمتر را برای کلاس [SmartPtr](../) فراهم می‌کند.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Y | نوع اشاره‌گری که برای مقایسه با اشاره‌گر جاری استفاده می‌شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| p | Y * | اشاره‌گری که برای مقایسه با اشاره‌گر جاری استفاده می‌شود. |

### مقدار بازگشت

True اگر شیء ارجاع‌شده توسط [SmartPtr](../) نسبت به p 'less' باشد و در غیر این صورت false.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const متد


معنای مقایسه کمتر را برای کلاس [SmartPtr](../) فراهم می‌کند.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Y | نوع اشاره‌گری که برای مقایسه با اشاره‌گر جاری استفاده می‌شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | اشاره‌گری که برای مقایسه با اشاره‌گر جاری استفاده می‌شود. |

### مقدار بازگشت

True اگر شیء ارجاع‌شده توسط [SmartPtr](../) نسبت به x 'less' باشد و در غیر اینصورت false.

## موارد مرتبط

* کلاس [SmartPtr](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)