---
title: IsControl()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد ما إذا كان الحرف الموجود عند الفهرس المحدد في مخزن الأحرف المحدد يُصنّف كحرف تحكم Unicode.
type: docs
weight: 66
url: /ar/system/char/iscontrol/
---
## Char::IsControl(const char_t *, int) طريقة

يحدد ما إذا كان الحرف الموجود عند الفهرس المحدد في مخزن الأحرف المحدد يُصنّف كحرف تحكم Unicode.

```cpp
static bool System::Char::IsControl(const char_t *str, int idx)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | مؤشر إلى بداية مخزن الأحرف |
| idx | int | فهرس يبدأ من الصفر في المخزن المحدد للحرف المراد اختباره |

### قيمة الإرجاع

True إذا كان الحرف عند الفهرس المحدد هو حرف تحكم Unicode، وإلا - false

## Char::IsControl(char_t) طريقة

يحدد ما إذا كان الحرف المحدد يُصنّف كحرف تحكم Unicode.

```cpp
static bool System::Char::IsControl(char_t c)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | الحرف المراد اختباره |

### قيمة الإرجاع

True إذا كان الحرف المحدد هو حرف تحكم Unicode، وإلا - false

## انظر أيضًا

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)