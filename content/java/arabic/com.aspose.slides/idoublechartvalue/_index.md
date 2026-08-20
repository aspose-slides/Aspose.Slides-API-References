---
title: IDoubleChartValue
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يمثل قيمة double يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من دفتر عمل مرتبط بالمخطط؛ 2) كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

يمثل قيمة double يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من دفتر عمل مرتبط بالمخطط؛ 2) كقيمة حرفية.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | يعيد أو يضبط قيمة double حرفية إذا DataSourceType = Charts.DataSourceType.DoubleLiterals. قراءة/كتابة double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | يعيد أو يضبط قيمة double حرفية إذا DataSourceType = Charts.DataSourceType.DoubleLiterals. قراءة/كتابة double. |
| [toDouble()](#toDouble--) | تحول إلى double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

يعيد أو يضبط قيمة double حرفية إذا DataSourceType = Charts.DataSourceType.DoubleLiterals. قراءة/كتابة double.

**القيمة المرجعة:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

يعيد أو يضبط قيمة double حرفية إذا DataSourceType = Charts.DataSourceType.DoubleLiterals. قراءة/كتابة double.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

تحول إلى double.

**القيمة المرجعة:**
double - Double value.