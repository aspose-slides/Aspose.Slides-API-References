---
title: IStringOrDoubleChartValue
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل قيمة نصية أو مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من مصنف مرتبط بالمخطط 2) كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/istringordoublechartvalue/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

تمثّل قيمة نصية أو مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من مصنف مرتبط بالمخطط؛ 2) كقيمة حرفية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | يرجع أو يعيّن النص الحرفي إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. قابل للقراءة والكتابة String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | يرجع أو يعيّن النص الحرفي إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. قابل للقراءة والكتابة String. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | يرجع أو يعيّن القيمة المزدوجة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.DoubleLiterals. قابل للقراءة والكتابة double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | يرجع أو يعيّن القيمة المزدوجة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.DoubleLiterals. قابل للقراءة والكتابة double. |
| [toDouble()](#toDouble--) | يحوّل القيمة إلى مزدوج. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


يرجع أو يعيّن النص الحرفي إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


يرجع أو يعيّن النص الحرفي إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


يرجع أو يعيّن القيمة المزدوجة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.DoubleLiterals. قابل للقراءة والكتابة double.

**الإرجاع:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


يرجع أو يعيّن القيمة المزدوجة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.DoubleLiterals. قابل للقراءة والكتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


يحّول القيمة إلى مزدوج.

**الإرجاع:**
double - قيمة مزدوجة double