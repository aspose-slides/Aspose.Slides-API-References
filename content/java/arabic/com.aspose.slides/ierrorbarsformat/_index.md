---
title: IErrorBarsFormat
second_title: مرجع API لـ Aspose.Slides للجاڤا
description: يمثل أشرطة الخطأ لسلسلة المخطط.
type: docs
url: /ar/com.aspose.slides/ierrorbarsformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

يمثل أشرطة الخطأ لسلسلة المخطط. قيم ErrorBars المخصصة موجودة في IChartDataPointCollection (في الخاصية [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل أو يضبط نوع أشرطة الخطأ. |
| [setType(int value)](#setType-int-) | يحصل أو يضبط نوع أشرطة الخطأ. |
| [getValueType()](#getValueType--) | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. |
| [setValueType(int value)](#setValueType-int-) | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. |
| [hasEndCap()](#hasEndCap--) | يحدد أنه لا يتم رسم غطاء نهائي على أشرطة الخطأ. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | يحدد أنه لا يتم رسم غطاء نهائي على أشرطة الخطأ. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي تُستخدم مع أنواع القيمة Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. |
| [setValue(float value)](#setValue-float-) | يحصل أو يضبط القيمة التي تُستخدم مع أنواع القيمة Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. |
| [getFormat()](#getFormat--) | يمثل تنسيق أشرطة الخطأ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق أشرطة الخطأ. |
| [isVisible()](#isVisible--) | يحصل أو يضبط ظهور أشرطة الخطأ. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط ظهور أشرطة الخطأ. |

### getType() {#getType--}
```
public abstract int getType()
```

يحصل أو يضبط نوع أشرطة الخطأ. قراءة/كتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**الإرجاع:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

يحصل أو يضبط نوع أشرطة الخطأ. قراءة/كتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصص لتحديد القيمة استخدم الخاصية [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. قراءة/كتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**الإرجاع:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصص لتحديد القيمة استخدم الخاصية [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. قراءة/كتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

يحدد أنه لا يتم رسم غطاء نهائي على أشرطة الخطأ. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

يحدد أنه لا يتم رسم غطاء نهائي على أشرطة الخطأ. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

يحصل أو يضبط القيمة التي تُستخدم مع أنواع القيمة Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. قراءة/كتابة float.

**الإرجاع:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

يحصل أو يضبط القيمة التي تُستخدم مع أنواع القيمة Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل تنسيق أشرطة الخطأ. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

يمثل تنسيق أشرطة الخطأ. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

يحصل أو يضبط ظهور أشرطة الخطأ. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

يحصل أو يضبط ظهور أشرطة الخطأ. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |