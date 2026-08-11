---
title: NotSameFailure()
second_title: مرجع API Aspose.Slides برای C++
description: فرمت‌گذاری شکست ادعای 'not same' برای خروجی.
type: docs
weight: 66
url: /fa/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) تابع

فرمت‌گذاری شکست ادعای 'not same' برای خروجی.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقدار LHS. |
| T2 | نوع مقدار RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | T1\& | مقدار LHS. |
| rhs | T2\& | مقدار RHS. |

### مقدار بازگشت

[Object](../../system/object/) متن خطا را محاط می‌کند.

## موارد مرتبط

* فضای نام [System::TestPredicates::Details](../)
* کتابخانه [Aspose.Slides](../../)