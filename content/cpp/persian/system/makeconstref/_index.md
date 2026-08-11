---
title: MakeConstRef
second_title: مرجع API Aspose.Slides برای C++
description: خصوصیت برای ساخت \"const reference\" از نوع عمومی اگر آن String یا نوع SmartPtr<> باشد.
type: docs
weight: 1769
url: /fa/system/makeconstref/
---
## MakeConstRef struct

Trait برای ساخت "const reference" به نوع عمومی اگر آن [String](../string/) یا نوع SmartPtr<> باشد.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)