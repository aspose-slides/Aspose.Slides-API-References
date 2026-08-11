---
title: Equals()
second_title: Aspose.Slides مرجع API لـ C++
description: يحدد مساواة القيمة المحددة باستخدام المشغل ==().
type: docs
weight: 66
url: /ar/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) function


يحدد مساواة القيمة المحددة باستخدام [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| The | نوع القيم التي يتم مقارنتها |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | المقارن الأول |
| value2 | T | المقارن الثاني |

### قيمة الإرجاع

True إذا كانت القيمة المحددة متساوية كما حُددت بواسطة [operator==()](../../system/operator_equal_equal/)، وإلا - false

## System::BoxedValueDetail::Equals(T, T) function


يحدد مساواة القيمة المحددة باستخدام الطريقة [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| The | نوع القيم التي يتم مقارنتها |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | المقارن الأول |
| value2 | T | المقارن الثاني |

### قيمة الإرجاع

True إذا كانت القيمة المحددة متساوية كما حُددت بواسطة الطريقة [Equals()](./)، وإلا - false

## انظر أيضًا

* النطاق [System::BoxedValueDetail](../)
* المكتبة [Aspose.Slides](../../)