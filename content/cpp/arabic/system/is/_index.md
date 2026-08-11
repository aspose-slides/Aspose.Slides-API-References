---
title: Is()
second_title: مرجع API Aspose.Slides للـ C++
description: ينفّذ ترجمة نمط إعلان 'is'.
type: docs
weight: 2302
url: /ar/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) دالة

ينفذ ترجمة نمط الإعلان 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| PatternT | النوع للتحقق منه. |
| ExpressionT | نوع التعبير الأيسر. |
| ResultT | نوع تعبير النتيجة. |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| left | const ExpressionT\& | التعبير الذي سيُفحص. |
| result | ResultT\& | المتغيّر الذي سيُعيّن إلى النوع المفحوص. |

### قيمة الإرجاع

true إذا نجح فحص النوع، false وإلا.

## System::Is(const ExpressionT\&, const ConstantT\&) دالة

ينفذ ترجمة نمط الثابت 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| ExpressionT | نوع التعبير الأيسر. |
| ConstantT | نوع تعبير الثابت. |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| left | const ExpressionT\& | التعبير الذي سيُفحص. |
| constant | const ConstantT\& | التعبير الذي سيُقارن مع الأيسر. |

### قيمة الإرجاع

true إذا نجح فحص النوع، false وإلا.

## System::Is(const E\&, const A\&) دالة

دالة مطابقة على المستوى الأعلى. تطبق نمطًا على قيمة.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| A | نوع النمط (يجب أن يرث من Details::Pattern). |
| E | نوع القيمة التي سيُطابق عليها. |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| e | const E\& | القيمة التي ستُطابق ضدها. |
| a | const A\& | النمط الذي سيُطبّق. |

### قيمة الإرجاع

true إذا كان النمط يطابق القيمة، false وإلا.

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)