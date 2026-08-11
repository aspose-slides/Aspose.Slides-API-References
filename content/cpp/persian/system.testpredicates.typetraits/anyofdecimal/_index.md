---
title: AnyOfDecimal
second_title: Aspose.Slides برای مرجع API C++
description: "بررسی می‌کند که حداقل یکی از آرگومان‌های نوع System::Decimal باشد. در این صورت، مقدار عضو value را به true تنظیم می‌کند، در غیر این صورت false است."
type: docs
weight: 92
url: /fa/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

بررسی می‌کند که حداقل یکی از آرگومان‌های نوع [System::Decimal](../../system/decimal/) باشد. در این صورت، مقدار عضو value را به true تنظیم می‌کند، در غیر این صورت false است.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## موارد مرتبط

* فضای نام [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)