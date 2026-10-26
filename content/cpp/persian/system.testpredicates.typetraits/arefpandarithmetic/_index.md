---
title: AreFPandArithmetic
second_title: مرجع API برای C++ Aspose.Slides
description: بررسی می‌کند که T1 عددی است و T2 نقطه شناور، یا برعکس. اگر چنین باشد، عضو value را به true تنظیم می‌کند؛ در غیر این صورت false است.
type: docs
weight: 79
url: /fa/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

بررسی می‌کند که **T1** عددی و **T2** نقطه شناور است، یا برعکس. اگر چنین باشد، مقدار عضو value را به true تنظیم می‌کند؛ در غیر این صورت false است.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## موارد مرتبط

* فضای نام [System::TestPredicates::TypeTraits](../)
* کتابخانه [Aspose.Slides](../../)