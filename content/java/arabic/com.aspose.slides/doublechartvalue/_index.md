---
title: DoubleChartValue
second_title: مرجع API لـ Aspose.Slides للجاوا
description: يمثل قيمة مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1 في خلية/خلايا دفتر العمل المرتبط بالمخطط 2 كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/doublechartvalue/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

يمثل قيمة مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا دفتر العمل المرتبط بالمخطط؛ 2) كقيمة حرفية.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAsCell()](#getAsCell--) | إرجاع أو تعيين خلية بيانات المخطط. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | إرجاع أو تعيين خلية بيانات المخطط. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | إرجاع أو تعيين القيمة كقيمة مزدوجة حرفية. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | إرجاع أو تعيين القيمة كقيمة مزدوجة حرفية. |
| [getData()](#getData--) | إرجاع أو تعيين كائن Data. |
| [setData(Object value)](#setData-java.lang.Object-) | إرجاع أو تعيين كائن Data. |
| [toDouble()](#toDouble--) | تحويل إلى مزدوج. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

إرجاع أو تعيين خلية بيانات المخطط. قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

إرجاع أو تعيين خلية بيانات المخطط. قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

إرجاع أو تعيين القيمة كقيمة مزدوجة حرفية. قراءة/كتابة مزدوج.

**الإرجاع:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

إرجاع أو تعيين القيمة كقيمة مزدوجة حرفية. قراءة/كتابة مزدوج.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

إرجاع أو تعيين كائن Data. قراءة/كتابة Object.

**الإرجاع:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

إرجاع أو تعيين كائن Data. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

تحويل إلى مزدوج.

**الإرجاع:**
double - إرجاع LiteralDouble إذا كان DataSourceType يساوي DoubleLiterals. إذا كان DataSourceType يساوي Worksheet يرجع قيمة الخلية المحولة بنجاح إلى مزدوج، وإلا يرجع NaN.