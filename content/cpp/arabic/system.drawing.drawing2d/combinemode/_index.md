---
title: CombineMode
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد كيف يتم دمج مناطق القص.
type: docs
weight: 170
url: /ar/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

يحدد كيف يتم دمج مناطق القص.

```cpp
enum class CombineMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Replace | 0 | يتم استبدال منطقة قص واحدة بأخرى. |
| Intersect | 1 | يتم دمج منطقتي القص بأخذ تقاطعهما. |
| Union | 2 | يتم دمج منطقتي القص بأخذ اتحادهما. |
| Xor | 3 | يتم دمج منطقتي القص بأخذ المساحة المحصورة في إحداهما فقط أو الأخرى، لكن ليس كليهما. |
| Exclude | 4 | يتم دمج منطقتي القص بأخذ مساحة المنطقة الأولى التي لا تتقاطع مع الثانية. |
| Complement | 5 | يتم دمج منطقتي القص بأخذ مساحة المنطقة الثانية التي لا تتقاطع مع الأولى. |

## انظر أيضًا

* نطاق الاسم [System::Drawing::Drawing2D](../)
* مكتبة [Aspose.Slides](../../)