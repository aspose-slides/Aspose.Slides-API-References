---
title: CachedChartValue
second_title: Aspose.Slides لمرجع API جافا
description: يمثل قيمة مخزّنة للمخطط مثل X و Y وحجم الفقاعات أو القيمة الرئيسية.
type: docs
url: /ar/com.aspose.slides/cachedchartvalue/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

يمثّل قيمة مخزنة للمخطط (مثل X، Y، حجم الفقاعات، أو القيمة الرئيسية).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [toString()](#toString--) | Returns a string representation of the cached value. |
| [toDouble()](#toDouble--) | Converts the cached value to a double. |
| [getData()](#getData--) | Gets the cached data object. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا للقيمة المخزنة.

**الإرجاع:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


يحَوِّل القيمة المخزنة إلى عدد مزدوج.

**الإرجاع:**
double - التمثيل الرقمي، أو Double.NaN إذا كان Data (\#getData.getData/\#setData(Object).setData(Object)) فارغًا أو لا يمكن تحويله إلى عدد مزدوج.
### getData() {#getData--}
```
public final Object getData()
```


يحصل على كائن البيانات المخزّن. للقراءة فقط Object .

**الإرجاع:**
java.lang.Object