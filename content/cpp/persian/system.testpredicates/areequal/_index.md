---
title: AreEqual()
second_title: Aspose.Slides برای مرجع API C++
description: آرگومان‌ها را برای ترجمه ادعای AreEqual به‌صورت برابر مقایسه می‌کند.
type: docs
weight: 14
url: /fa/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) تابع


مقایسه برابر آرگومان‌ها برای ترجمه ادعای AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | مقدار LHS. |
| rhs | T2\&& | مقدار RHS. |

### مقدار بازگشت

نتیجهٔ ادعای به سبک gtest.

## موارد مرتبط

* فضای‌نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)