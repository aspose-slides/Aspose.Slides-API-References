---
title: ChartPortionFormat
second_title: مرجع API Aspose.Slides للـ Java
description: تحتوي هذه الفئة على خصائص تنسيق جزء المخطط المستخدمة في المخططات.
type: docs
url: /ar/com.aspose.slides/chartportionformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)  
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

هذه الفئة تحتوي على خصائص تنسيق جزء المخطط المستخدمة في المخططات. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المحددة للجزء المعين. وهذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذلك في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) التي تُرجع مثيلًا من [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. طويل للقراءة فقط.

**القيمة المرجعة:**  
long