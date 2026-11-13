---
title: ICachedChartValue
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل قيمة مخزنة للمخطط مثل X Y حجم الفقاعة أو القيمة الرئيسية.
type: docs
url: /ar/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

يمثل قيمة مخزنة للمخطط (مثل X, Y, حجم الفقاعة، أو القيمة الرئيسية).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getData()](#getData--) | يحصل على كائن البيانات المخزّن. |
| [toDouble()](#toDouble--) | يحوّل القيمة المخزنة إلى double. |
### getData() {#getData--}
```
public abstract Object getData()
```

يحصل على كائن البيانات المخزّن. للقراءة فقط Object .

**الإرجاع:**  
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

يحوّل القيمة المخزنة إلى double.

**الإرجاع:**  
double - التمثيل الرقمي، أو Double.NaN إذا كانت Data (\#getData.getData) فارغة أو لا يمكن تحويلها إلى double.