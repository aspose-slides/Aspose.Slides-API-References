---
title: ErrorBarsFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل أشرطة الخطأ لسلسلة المخطط.
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

يمثل أشرطة الخطأ لسلسلة المخطط. قيم ErrorBars المخصصة موجودة في IChartDataPointCollection (في الخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## الطرق

| طريقة | وصف |
| --- | --- |
| [getType()](#getType--) | يسترجع أو يعيّن نوع أشرطة الخطأ. |
| [setType(int value)](#setType-int-) | يسترجع أو يعيّن نوع أشرطة الخطأ. |
| [getValueType()](#getValueType--) | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. |
| [setValueType(int value)](#setValueType-int-) | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. |
| [hasEndCap()](#hasEndCap--) | يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. |
| [getValue()](#getValue--) | يسترجع أو يعيّن القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. |
| [setValue(float value)](#setValue-float-) | يسترجع أو يعيّن القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. |
| [getFormat()](#getFormat--) | يمثل تنسيق أشرطة الخطأ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق أشرطة الخطأ. |
| [getChart()](#getChart--) | يعيد المخطط الأب. |
| [isVisible()](#isVisible--) | يسترجع أو يعيّن رؤية أشرطة الخطأ. |
| [setVisible(boolean value)](#setVisible-boolean-) | يسترجع أو يعيّن رؤية أشرطة الخطأ. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأب لتنسيق التعبئة. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأب لتنسيق التعبئة. |

### getType() {#getType--}
```
public final int getType()
```

يسترجع أو يعيّن نوع أشرطة الخطأ. قراءة/كتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**الإرجاع:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يسترجع أو يعيّن نوع أشرطة الخطأ. قراءة/كتابة [ErrorBarType](../../com.aspose.slides/errorbartype).

**المعلمات:**  
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصص لاستخدام القيمة استخدم خاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. في حالة نوع القيمة Fixed أو Percentage أو StandardDeviation استخدم خاصية Value لتحديد القيمة. قراءة/كتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**الإرجاع:**  
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصص لاستخدام القيمة استخدم خاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) لنقطة البيانات المحددة في مجموعة DataPoints للسلسلة. في حالة نوع القيمة Fixed أو Percentage أو StandardDeviation استخدم خاصية Value لتحديد القيمة. قراءة/كتابة [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**المعلمات:**  
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

يحدد عدم رسم غطاء نهائي على أشرطة الخطأ. قراءة/كتابة boolean.

**المعلمات:**  
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

يسترجع أو يعيّن القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. في أي حالة أخرى سيعيد NaN. قراءة/كتابة float.

**الإرجاع:**  
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

يسترجع أو يعيّن القيمة التي تُستخدم مع أنواع القيم Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. في أي حالة أخرى سيعيد NaN. قراءة/كتابة float.

**المعلمات:**  
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل تنسيق أشرطة الخطأ. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

يمثل تنسيق أشرطة الخطأ. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**المعلمات:**  
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأب. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

يسترجع أو يعيّن رؤية أشرطة الخطأ. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

يسترجع أو يعيّن رؤية أشرطة الخطأ. قراءة/كتابة boolean.

**المعلمات:**  
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأب لتنسيق التعبئة. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأب لتنسيق التعبئة. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)