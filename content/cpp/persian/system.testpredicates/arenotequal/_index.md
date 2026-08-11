---
title: AreNotEqual()
second_title: Aspose.Slides برای مرجع API C++
description: مقایسه‌های نابرابر آرگومان‌ها برای ترجمه ادعای AreEqual.
type: docs
weight: 40
url: /fa/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) تابع

تطبیق‌های نابرابر آرگومان‌ها برای ترجمه ادعای AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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

نتیجه ادعای سبک gtest.

## همچنین ببینید

* فضا نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)