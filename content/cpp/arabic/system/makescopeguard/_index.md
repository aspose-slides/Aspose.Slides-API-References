---
title: MakeScopeGuard()
second_title: مرجع API Aspose.Slides للـ C++
description: دالة مصنع تقوم بإنشاء مثيلات من فئة ScopedGuard.
type: docs
weight: 2809
url: /ar/system/makescopeguard/
---
## System::MakeScopeGuard(F) دالة

دالة مصنع تقوم بإنشاء مثيلات من فئة ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ال | نوع كائن الدالة الذي سيتم استدعاؤه بواسطة كائن ScopedGuard المُنشأ |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| f | F | كائن الدالة لتمريره إلى مُنشئ فئة ScopedGuard. |

### قيمة الإرجاع

مثيل جديد من فئة ScopedGuard

## انظر أيضاً

* بنية [ScopeGuard](../scopeguard/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)