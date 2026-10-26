---
title: BothArrayOrList
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا هر دو آرگومان نوع آرایه یا لیست هستند. در این صورت، مقدار عضو value برابر true تنظیم می‌شود، در غیر این صورت برابر false تنظیم می‌شود.
type: docs
weight: 131
url: /fa/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

بررسی می‌کند که آیا هر دو آرگومان نوع آرایه یا لیست هستند. در این صورت، مقدار عضو value برابر true تنظیم می‌شود، در غیر این صورت برابر false تنظیم می‌شود.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## موارد مرتبط

* فضای نام [System::TestPredicates::TypeTraits](../)
* کتابخانه [Aspose.Slides](../../)