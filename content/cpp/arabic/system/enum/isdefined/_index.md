---
title: IsDefined()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كانت القيمة المحددة عضوًا في نوع التعداد E.
type: docs
weight: 27
url: /ar/system/enum/isdefined/
---
## Enum::IsDefined(E) الطريقة

يحدد ما إذا كانت القيمة المحددة عضوًا في نوع التعداد **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | E | القيمة التي يجب فحصها |

### قيمة الإرجاع

True إذا كان **value** عضوًا في تعداد **E**، وإلا - false

## Enum::IsDefined(T) الطريقة

يحدد ما إذا كانت القيمة المحددة عضوًا في نوع التعداد **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | T | القيمة التي يجب فحصها |

### قيمة الإرجاع

True إذا كان **value** عضوًا في تعداد **T**، وإلا - false

## Enum::IsDefined(const String\&) الطريقة

يحدد ما إذا كانت القيمة ذات الاسم المحدد من بين أعضاء تعداد **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | const [String](../../string/)\& | الاسم الذي يجب فحصه |

### قيمة الإرجاع

True إذا كان هناك عضو في تعداد **E** يحمل الاسم المحدد.

## انظر أيضًا

* تعريف نوع [UnderlyingType](../underlyingtype/)
* فئة [String](../../string/)
* بنية [Enum](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)