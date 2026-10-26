---
title: MakeConstRef
second_title: مرجع API Aspose.Slides للغة C++
description: سمة لإنشاء نوع عام \"إشارة ثابتة\" إذا كان String أو نوع SmartPtr<>.
type: docs
weight: 1769
url: /ar/system/makeconstref/
---
## MakeConstRef بنية


سمة لإنشاء نوع عام "إشارة ثابتة" إذا كان [String](../string/) أو نوع SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)