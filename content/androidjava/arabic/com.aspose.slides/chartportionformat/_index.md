---
title: ChartPortionFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: هذه الفئة تحتوي على خصائص تنسيق جزء المخطط المستخدمة في المخططات.
type: docs
url: /ar/com.aspose.slides/chartportionformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

هذه الفئة تحتوي على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

هذه الفئة تُستخدم لإرجاع ومعالجة خصائص تنسيق جزء النص المُحددة للجزء المعين. يعني هذا أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معايير التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) التي تُرجع مثيلًا من [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. لقراءة فقط long.

**الإرجاع:**
long