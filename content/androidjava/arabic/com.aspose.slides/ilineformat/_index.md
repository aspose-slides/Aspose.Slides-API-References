---
title: ILineFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تنسيق الخط.
type: docs
url: /ar/com.aspose.slides/ilineformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

يمثل تنسيق الخط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | يعيد true إذا لم يُعرَّف تنسيق الخط (كما هو مباشرةً عند الإنشاء، الافتراضي). |
| [getFillFormat()](#getFillFormat--) | يعيد تنسيق التعبئة للخط. |
| [getSketchFormat()](#getSketchFormat--) | يعيد تنسيق المخطط للخط. |
| [getWidth()](#getWidth--) | يعيد أو يضبط عرض الخط. |
| [setWidth(double value)](#setWidth-double-) | يعيد أو يضبط عرض الخط. |
| [getDashStyle()](#getDashStyle--) | يعيد أو يضبط نمط الشرط للخط. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | يعيد أو يضبط نمط الشرط للخط. |
| [getCustomDashPattern()](#getCustomDashPattern--) | يعيد أو يضبط نمط الشرط المخصص. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | يعيد أو يضبط نمط الشرط المخصص. |
| [getCapStyle()](#getCapStyle--) | يعيد أو يضبط نمط نهايات الخط. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | يعيد أو يضبط نمط نهايات الخط. |
| [getStyle()](#getStyle--) | يعيد أو يضبط نمط الخط. |
| [setStyle(byte value)](#setStyle-byte-) | يعيد أو يضبط نمط الخط. |
| [getAlignment()](#getAlignment--) | يعيد أو يضبط محاذاة الخط. |
| [setAlignment(byte value)](#setAlignment-byte-) | يعيد أو يضبط محاذاة الخط. |
| [getJoinStyle()](#getJoinStyle--) | يعيد أو يضبط نمط وصل الخطوط. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | يعيد أو يضبط نمط وصل الخطوط. |
| [getMiterLimit()](#getMiterLimit--) | يعيد أو يضبط حد القطع للخط. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | يعيد أو يضبط حد القطع للخط. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | يعيد أو يضبط نمط رأس السهم في بداية الخط. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | يعيد أو يضبط نمط رأس السهم في بداية الخط. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | يعيد أو يضبط نمط رأس السهم في نهاية الخط. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | يعيد أو يضبط نمط رأس السهم في نهاية الخط. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | يعيد أو يضبط عرض رأس السهم في بداية الخط. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | يعيد أو يضبط عرض رأس السهم في بداية الخط. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | يعيد أو يضبط عرض رأس السهم في نهاية الخط. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | يعيد أو يضبط عرض رأس السهم في نهاية الخط. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | يعيد أو يضبط طول رأس السهم في بداية الخط. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | يعيد أو يضبط طول رأس السهم في بداية الخط. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | يعيد أو يضبط طول رأس السهم في نهاية الخط. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | يعيد أو يضبط طول رأس السهم في نهاية الخط. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | يحدد ما إذا كان مثلي LineFormat متساويين. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

يعيد true إذا لم يُعرَّف تنسيق الخط (كما هو مباشرةً عند الإنشاء، الافتراضي). للقراءة فقط منطقية.

**القيمة المرجعة:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

يعيد تنسيق التعبئة للخط. للقراءة فقط [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**القيمة المرجعة:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

يعيد تنسيق المخطط للخط. للقراءة فقط [ISketchFormat](../../com.aspose.slides/isketchformat).

**القيمة المرجعة:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

يعيد أو يضبط عرض الخط. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

يعيد أو يضبط عرض الخط. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

يعيد أو يضبط نمط الشرط للخط. قابل للقراءة والكتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**القيمة المرجعة:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

يعيد أو يضبط نمط الشرط للخط. قابل للقراءة والكتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

يعيد أو يضبط نمط الشرط المخصص. قابل للقراءة والكتابة float[].

**القيمة المرجعة:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

يعيد أو يضبط نمط الشرط المخصص. قابل للقراءة والكتابة float[].

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

يعيد أو يضبط نمط نهايات الخط. قابل للقراءة والكتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**القيمة المرجعة:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

يعيد أو يضبط نمط نهايات الخط. قابل للقراءة والكتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

يعيد أو يضبط نمط الخط. قابل للقراءة والكتابة [LineStyle](../../com.aspose.slides/linestyle).

**القيمة المرجعة:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

يعيد أو يضبط نمط الخط. قابل للقراءة والكتابة [LineStyle](../../com.aspose.slides/linestyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

يعيد أو يضبط محاذاة الخط. قابل للقراءة والكتابة [LineAlignment](../../com.aspose.slides/linealignment).

**القيمة المرجعة:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

يعيد أو يضبط محاذاة الخط. قابل للقراءة والكتابة [LineAlignment](../../com.aspose.slides/linealignment).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

يعيد أو يضبط نمط وصل الخطوط. قابل للقراءة والكتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**القيمة المرجعة:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

يعيد أو يضبط نمط وصل الخطوط. قابل للقراءة والكتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

يعيد أو يضبط حد القطع للخط. قابل للقراءة والكتابة float.

**القيمة المرجعة:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

يعيد أو يضبط حد القطع للخط. قابل للقراءة والكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

يعيد أو يضبط نمط رأس السهم في بداية الخط. قابل للقراءة والكتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**القيمة المرجعة:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

يعيد أو يضبط نمط رأس السهم في بداية الخط. قابل للقراءة والكتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

يعيد أو يضبط نمط رأس السهم في نهاية الخط. قابل للقراءة والكتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**القيمة المرجعة:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

يعيد أو يضبط نمط رأس السهم في نهاية الخط. قابل للقراءة والكتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

يعيد أو يضبط عرض رأس السهم في بداية الخط. قابل للقراءة والكتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**القيمة المرجعة:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

يعيد أو يضبط عرض رأس السهم في بداية الخط. قابل للقراءة والكتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

يعيد أو يضبط عرض رأس السهم في نهاية الخط. قابل للقراءة والكتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**القيمة المرجعة:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

يعيد أو يضبط عرض رأس السهم في نهاية الخط. قابل للقراءة والكتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

يعيد أو يضبط طول رأس السهم في بداية الخط. قابل للقراءة والكتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**القيمة المرجعة:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

يعيد أو يضبط طول رأس السهم في بداية الخط. قابل للقراءة والكتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

يعيد أو يضبط طول رأس السهم في نهاية الخط. قابل للقراءة والكتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**القيمة المرجعة:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

يعيد أو يضبط طول رأس السهم في نهاية الخط. قابل للقراءة والكتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

يحدد ما إذا كان مثلي LineFormat متساويين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | الـ LineFormat للمقارنة مع الـ LineFormat الحالي. |

**القيمة المرجعة:**
boolean - **true** إذا كان الـ LineFormat المحدد مساويًا للـ LineFormat الحالي؛ وإلا **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).