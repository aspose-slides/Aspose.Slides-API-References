---
title: Coalesce()
second_title: Aspose.Slides لـ C++ مرجع API
description: تنفيذ ترجمة عامل '??' للأنواع غير القابلة للفرغ.
type: docs
weight: 170
url: /ar/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) طريقة

تنفيذ ترجمة عامل '??' للأنواع غير القابلة للفراغ.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T0 | نوع قيمة LHS. |
| T1 | نوع lambda الذي يغلف تعبير RHS. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0 | قيمة LHS. |
| func | T1 | تعبير RHS. |

### قيمة الإرجاع

إذا كانت قيمة LHS ليست null، يتم إرجاع LHS، وإلا يتم حساب تعبير RHS وإرجاع النتيجة.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) طريقة

تنفيذ ترجمة عامل '??' للأنواع القابلة للفراغ.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T0 | نوع قيمة LHS. |
| T1 | نوع lambda الذي يغلف تعبير RHS. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | قيمة LHS. |
| func | T1 | تعبير RHS. |

### قيمة الإرجاع

إذا كانت قيمة LHS ليست null، يتم إرجاع LHS، وإلا يتم حساب تعبير RHS وإرجاع النتيجة.

## انظر أيضًا

* فئة [ObjectExt](../)
* فئة [Nullable](../../nullable/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)