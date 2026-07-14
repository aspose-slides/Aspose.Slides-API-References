---
title: IErrorBarsFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل أشرطة الخطأ لسلسلة المخطط.
type: docs
url: /ar/com.aspose.slides/ierrorbarsformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

يمثل أشرطة الخطأ لسلسلة المخطط. قيم ErrorBars المخصصة موجودة في IChartDataPointCollection (في خاصية [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## الطرق

| Method | Description |
| --- | --- |
| [getType()](#getType--) | يقوم بالحصول على أو تعيين نوع أشرطة الخطأ. |
| [setType(int value)](#setType-int-) | يقوم بالحصول على أو تعيين نوع أشرطة الخطأ. |
| [getValueType()](#getValueType--) | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. |
| [setValueType(int value)](#setValueType-int-) | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. |
| [hasEndCap()](#hasEndCap--) | يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. |
| [getValue()](#getValue--) | يقوم بالحصول على أو تعيين القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. |
| [setValue(float value)](#setValue-float-) | يقوم بالحصول على أو تعيين القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. |
| [getFormat()](#getFormat--) | يمثل تنسيق أشرطة الخطأ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق أشرطة الخطأ. |
| [isVisible()](#isVisible--) | يقوم بالحصول على أو تعيين رؤية أشرطة الخطأ. |
| [setVisible(boolean value)](#setVisible-boolean-) | يقوم بالحصول على أو تعيين رؤية أشرطة الخطأ. |

### getType() {#getType--}
```
public abstract int getType()
```

يقوم بالحصول على أو تعيين نوع أشرطة الخطأ. قراءة/كتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**القيمة المرجعة:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

يقوم بالحصول على أو تعيين نوع أشرطة الخطأ. قراءة/كتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصصة لتحديد القيمة استخدم خاصية [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. قراءة/كتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**القيمة المرجعة:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصصة لتحديد القيمة استخدم خاصية [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. قراءة/كتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. قراءة/كتابة boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

يقوم بالحصول على أو تعيين القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. قراءة/كتابة float.

**القيمة المرجعة:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

يقوم بالحصول على أو تعيين القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. قراءة/كتابة float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل تنسيق أشرطة الخطأ. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

يمثل تنسيق أشرطة الخطأ. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

يقوم بالحصول على أو تعيين رؤية أشرطة الخطأ. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

يقوم بالحصول على أو تعيين رؤية أشرطة الخطأ. قراءة/كتابة boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |