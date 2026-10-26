---
title: IDoubleChartValue
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثّل قيمة مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من المصنف المتعلق بالمخطط، 2) كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/idoublechartvalue/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

يمثِّل قيمة مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من المصنف المتعلق بالمخطط؛ 2) كقيمة حرفية.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | إرجاع أو تعيين القيمة المزدوجة الحرفية إذا كان DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | إرجاع أو تعيين القيمة المزدوجة الحرفية إذا كان DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | تحويل إلى double. |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

إرجاع أو تعيين القيمة المزدوجة الحرفية إذا كان DataSourceType = Charts.DataSourceType.DoubleLiterals. قراءة/كتابة double.

**الإرجاع:**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

إرجاع أو تعيين القيمة المزدوجة الحرفية إذا كان DataSourceType = Charts.DataSourceType.DoubleLiterals. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

تحويل إلى double.

**الإرجاع:**
double - قيمة مزدوجة.