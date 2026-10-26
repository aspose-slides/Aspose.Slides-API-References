---
title: AreNotEqual()
second_title: Aspose.Slides برای C++ مرجع API
description: آرگومان‌ها را برای مقایسهٔ نامساوی در ادعای AreNotEqual ترجمه می‌کند.
type: docs
weight: 131
url: /fa/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function


Not-equal آرگومان‌ها را برای ترجمهٔ ادعای AreNotEqual مقایسه می‌کند.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

نتیجهٔ ادعای با قالب gtest.

## موارد مرتبط

* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)