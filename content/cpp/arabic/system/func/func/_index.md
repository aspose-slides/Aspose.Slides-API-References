---
title: Func()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: منشئ افتراضي ينشئ null-Func.
type: docs
weight: 1
url: /ar/system/func/func/
---
## Func::Func() منشئ

منشئ افتراضي ينشئ null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) منشئ

منشئ يقوم بإنشاء كائن [Func](../) ويعيّن القيمة (إما رد نداء فعلي أو nullptr) إليه.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### معلمات القالب

| معاملة | الوصف |
| --- | --- |
| T | نوع الوسيط. |

### المعاملات

| معاملة | نوع | الوصف |
| --- | --- | --- |
| arg | T\&& | معاملة. |

## Func::Func(const Func\&) منشئ

منشئ النسخ.

```cpp
System::Func<Args>::Func(const Func &func)
```

### المعاملات

| معاملة | نوع | الوصف |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) لنسخ البيانات من. |

## Func::Func(Func\&&) منشئ

منشئ النقل.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### المعاملات

| معاملة | نوع | الوصف |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) لنقل البيانات من. |

## انظر أيضًا

* الفئة [Func](../)
* المجال [System](../../)
* المكتبة [Aspose.Slides](../../../)