---
title: ScopeGuard
second_title: Aspose.Slides لواجهة برمجة التطبيقات (API) للغة C++
description: فئة الخدمة التي توفر خدمات لتشغيل كائن دالة معين عندما يخرج كائن من الفئة من النطاق.
type: docs
weight: 1886
url: /ar/system/scopeguard/
---
## هيكل ScopeGuard


فئة الخدمة التي توفر خدمات لتشغيل كائن دالة معين عندما يخرج كائن من الفئة من النطاق.

```cpp
template<typename F>class ScopeGuard
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| F | نوع كائن الدالة الذي تستدعيه أمثلة فئة ScopedGuard |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Disable](./disable/)() | يعطل استدعاء الحارس. |
|  [ScopeGuard](./scopeguard/)(F) | ينشئ مثيلاً يتم إعداده لاستدعاء كائن الدالة المحدد. |
|  [~ScopeGuard](./~scopeguard/)() | ينفذ كائن الدالة الممرّر إلى المُنشئ. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)