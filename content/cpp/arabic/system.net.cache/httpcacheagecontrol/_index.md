---
title: HttpCacheAgeControl
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُستخدم CacheAgeControl لتحديد التفضيلات فيما يتعلق بعمر العنصر المخزن في الذاكرة المؤقتة والحدّاثة.
type: docs
weight: 53
url: /ar/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl عدد

CacheAgeControl يُستخدم لتحديد التفضيلات فيما يتعلق بعمر العنصر المخزن في الذاكرة المؤقتة والحدّاثة.

```cpp
enum class HttpCacheAgeControl
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | للاستخدام الداخلي فقط. |
| MinFresh | 1 | يمكن أخذ المحتوى من الذاكرة المؤقتة إذا كان الوقت المتبقي قبل الانتهاء أكبر من أو يساوي الوقت المحدد بهذه القيمة. |
| MaxAge | 2 | يمكن أخذ المحتوى من الذاكرة المؤقتة حتى يصبح أقدم من العمر المحدد بهذه القيمة. |
| MaxStale | 4 | يمكن أخذ المحتوى من الذاكرة المؤقتة بعد انتهاء صلاحيته حتى يمر الوقت المحدد بهذه القيمة. |
| MaxAgeAndMinFresh | 3 | MaxAge و MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge و MaxStale. |

## انظر أيضًا

* Namespace [System::Net::Cache](../)
* Library [Aspose.Slides](../../)