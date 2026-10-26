---
title: AreNotSame()
second_title: مرجع API Aspose.Slides برای C++
description: Are-not-same آرگومان‌ها را برای ترجمهٔ ادعای AreSame مقایسه می‌کند.
type: docs
weight: 92
url: /fa/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) تابع

Are-not-same-compares آرگومان‌ها برای صحت‌سنجی AreSame ترجمه می‌شود.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |

### مقدار بازگشت

نتیجهٔ ادعای به سبک gtest.

## موارد مرتبط

* فضای نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)