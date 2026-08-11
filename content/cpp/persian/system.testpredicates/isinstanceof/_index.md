---
title: IsInstanceOf()
second_title: مرجع API Aspose.Slides برای C++
description: Is-instance-of آرگومان‌ها را برای ترجمه ادعای IsInstanceOf مقایسه می‌کند.
type: docs
weight: 118
url: /fa/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo&, const T&) تابع

Is-instance-of-آرگومان‌ها را برای ترجمه ادعای IsInstanceOf مقایسه می‌کند.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع آرگومان. |

### آرگومان‌ها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | شیء typeInfo که نمایانگر یک نوع است که نوع **obj** نسبت به آن مقایسه می‌شود |
| obj | const T\& | یک شیء که نوع آن برای مقایسه با نوع مشخص شده استفاده می‌شود |

### مقدار بازگشت

نتیجهٔ ادعایی به سبک gtest.

## موارد مرتبط

* کلاس [TypeInfo](../../system/typeinfo/)
* فضای نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)