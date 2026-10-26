---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides برای مرجع API C++
description: ساختار Trait برای تبدیل نوع آرگومان به یک weak-pointer، اگر نوع آن اشاره‌گر باشد.
type: docs
weight: 2016
url: /fa/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter ساختار

Trait struct برای تبدیل نوع آرگومان به یک weak-pointer، اگر نوع آن اشاره‌گر باشد.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)