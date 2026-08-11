---
title: WeakPtrFromTypeParameter
second_title: مرجع API ل Aspose.Slides للغة C++
description: هيكل سمة لتحويل نوع الوسيط إلى مؤشر ضعيف، إذا كان من نوع المؤشر.
type: docs
weight: 2016
url: /ar/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

هيكل سمة لتحويل نوع الوسيط إلى مؤشر ضعيف، إذا كان من نوع المؤشر.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)