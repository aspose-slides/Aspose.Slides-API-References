---
title: ErrorBarsFormat
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل أشرطة الأخطاء لسلسلة المخطط.
type: docs
url: /ar/com.aspose.slides/errorbarsformat/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

يمثل أشرطة الأخطاء في سلسلة المخطط. القيم المخصصة لـ ErrorBars موجودة في IChartDataPointCollection (في خاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## الطرق

| Method | Description |
| --- | --- |
| [getType()](#getType--) | يحصل على أو يضبط نوع أشرطة الأخطاء. |
| [setType(int value)](#setType-int-) | يحصل على أو يضبط نوع أشرطة الأخطاء. |
| [getValueType()](#getValueType--) | يمثل الطرق الممكنة لتحديد طول أشرطة الأخطاء. |
| [setValueType(int value)](#setValueType-int-) | يمثل الطرق الممكنة لتحديد طول أشرطة الأخطاء. |
| [hasEndCap()](#hasEndCap--) | يحدد أنه لا يتم رسم قبضة نهائية على أشرطة الأخطاء. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | يحدد أنه لا يتم رسم قبضة نهائية على أشرطة الأخطاء. |
| [getValue()](#getValue--) | يحصل على أو يضبط القيمة التي تُستخدم مع الأنواع Fixed وPercentage وStandardDeviation لتحديد طول أشرطة الأخطاء. |
| [setValue(float value)](#setValue-float-) | يحصل على أو يضبط القيمة التي تُستخدم مع الأنواع Fixed وPercentage وStandardDeviation لتحديد طول أشرطة الأخطاء. |
| [getFormat()](#getFormat--) | يمثل تنسيق أشرطة الأخطاء. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق أشرطة الأخطاء. |
| [getChart()](#getChart--) | يرجع المخطط الأب. |
| [isVisible()](#isVisible--) | يحصل على أو يضبط رؤية أشرطة الأخطاء. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل على أو يضبط رؤية أشرطة الأخطاء. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأب لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأب لـ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

يحصل على أو يضبط نوع أشرطة الأخطاء. قابل للقراءة والكتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**القيمة المرجعة:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يحصل على أو يضبط نوع أشرطة الأخطاء. قابل للقراءة والكتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

يمثل الطرق الممكنة لتحديد طول أشرطة الأخطاء. في حالة نوع القيمة المخصص لتحديد القيمة استخدم الخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. في حالة النوع Fixed أو Percentage أو StandardDeviation استخدم خاصية Value لتحديد القيمة. قابل للقراءة والكتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**القيمة المرجعة:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

يمثل الطرق الممكنة لتحديد طول أشرطة الأخطاء. في حالة نوع القيمة المخصص لتحديد القيمة استخدم الخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. في حالة النوع Fixed أو Percentage أو StandardDeviation استخدم خاصية Value لتحديد القيمة. قابل للقراءة والكتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

يحدد أنه لا يتم رسم قبضة نهائية على أشرطة الأخطاء. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

يحدد أنه لا يتم رسم قبضة نهائية على أشرطة الأخطاء. قابل للقراءة والكتابة boolean.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

يحصل على أو يضبط القيمة التي تُستخدم مع الأنواع Fixed وPercentage وStandardDeviation لتحديد طول أشرطة الأخطاء. في أي حالة أخرى سيعيد NaN. قابل للقراءة والكتابة float.

**القيمة المرجعة:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

يحصل على أو يضبط القيمة التي تُستخدم مع الأنواع Fixed وPercentage وStandardDeviation لتحديد طول أشرطة الأخطاء. في أي حالة أخرى سيعيد NaN. قابل للقراءة والكتابة float.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل تنسيق أشرطة الأخطاء. قابل للقراءة والكتابة [IFormat](../../com.aspose.slides/iformat).

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

يمثل تنسيق أشرطة الأخطاء. قابل للقراءة والكتابة [IFormat](../../com.aspose.slides/iformat).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

يحصل على أو يضبط رؤية أشرطة الأخطاء. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

يحصل على أو يضبط رؤية أشرطة الأخطاء. قابل للقراءة والكتابة boolean.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأب لـ FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأب لـ FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)