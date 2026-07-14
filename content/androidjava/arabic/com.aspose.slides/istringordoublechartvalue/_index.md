---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل قيمة نصية أو عددية مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1 في خلية/خلايا ورقة العمل المرتبطة بالمخطط 2 كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/istringordoublechartvalue/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

يمثل قيمة نصية أو عددية مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا ورقة العمل المرتبطة بالمخطط؛ 2) كقيمة حرفية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | إرجاع أو تعيين السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | إرجاع أو تعيين السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | إرجاع أو تعيين العدد المزدوج الحرفي إذا كانت الخاصية DataSourceType هي DataSourceType.DoubleLiterals. قراءة/كتابة double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | إرجاع أو تعيين العدد المزدوج الحرفي إذا كانت الخاصية DataSourceType هي DataSourceType.DoubleLiterals. قراءة/كتابة double. |
| [toDouble()](#toDouble--) | تحويل القيمة إلى double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

إرجاع أو تعيين السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

إرجاع أو تعيين السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

إرجاع أو تعيين العدد المزدوج الحرفي إذا كانت الخاصية DataSourceType هي DataSourceType.DoubleLiterals. قراءة/كتابة double.

**الإرجاع:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

إرجاع أو تعيين العدد المزدوج الحرفي إذا كانت الخاصية DataSourceType هي DataSourceType.DoubleLiterals. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

تحويل القيمة إلى double.

**الإرجاع:**
double - Double value double