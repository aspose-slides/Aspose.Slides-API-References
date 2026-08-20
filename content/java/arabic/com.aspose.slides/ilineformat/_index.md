---
title: ILineFormat
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل تنسيق خط.
type: docs
url: /ar/com.aspose.slides/ilineformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

يمثل تنسيق سطر.
## الطرق

| طريقة | وصف |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Returns true if line format is not defined (as just created, default). |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns or sets the width of a line. |
| [setWidth(double value)](#setWidth-double-) | Returns or sets the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns or sets the line dash style. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Returns or sets the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns or sets the custom dash pattern. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returns or sets the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns or sets the line cap style. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Returns or sets the line cap style. |
| [getStyle()](#getStyle--) | Returns or sets the line style. |
| [setStyle(byte value)](#setStyle-byte-) | Returns or sets the line style. |
| [getAlignment()](#getAlignment--) | Returns or sets the line alignment. |
| [setAlignment(byte value)](#setAlignment-byte-) | Returns or sets the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns or sets the lines join style. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Returns or sets the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns or sets the miter limit of a line. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Returns or sets the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns or sets the arrowhead style at the beginning of a line. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Returns or sets the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns or sets the arrowhead style at the end of a line. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Returns or sets the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns or sets the arrowhead width at the beginning of a line. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Returns or sets the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns or sets the arrowhead width at the end of a line. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Returns or sets the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns or sets the arrowhead length at the beginning of a line. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Returns or sets the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns or sets the arrowhead length at the end of a line. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Returns or sets the arrowhead length at the end of a line. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determines whether the two LineFormat instances are equal. |
| [getEffective()](#getEffective--) | Gets effective line formatting data with the inheritance applied. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

**القيمة المرجعة:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

إرجاع تنسيق التعبئة لسطر. قراءة فقط [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**القيمة المرجعة:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

إرجاع تنسيق الرسم لسطر. قراءة فقط [ISketchFormat](../../com.aspose.slides/isketchformat).

**القيمة المرجعة:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

إرجاع أو ضبط عرض السطر. قراءة/كتابة double.

**القيمة المرجعة:**  
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

إرجاع أو ضبط عرض السطر. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

إرجاع أو ضبط نمط الشرط للسطر. قراءة/كتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**القيمة المرجعة:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

إرجاع أو ضبط نمط الشرط للسطر. قراءة/كتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

إرجاع أو ضبط نمط الشرط المخصص. قراءة/كتابة float[].

**القيمة المرجعة:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

إرجاع أو ضبط نمط الشرط المخصص. قراءة/كتابة float[].

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

إرجاع أو ضبط نمط الطرف للسطر. قراءة/كتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**القيمة المرجعة:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

إرجاع أو ضبط نمط الطرف للسطر. قراءة/كتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

إرجاع أو ضبط نمط السطر. قراءة/كتابة [LineStyle](../../com.aspose.slides/linestyle).

**القيمة المرجعة:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

إرجاع أو ضبط نمط السطر. قراءة/كتابة [LineStyle](../../com.aspose.slides/linestyle).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

إرجاع أو ضبط محاذاة السطر. قراءة/كتابة [LineAlignment](../../com.aspose.slides/linealignment).

**القيمة المرجعة:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

إرجاع أو ضبط محاذاة السطر. قراءة/كتابة [LineAlignment](../../com.aspose.slides/linealignment).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

إرجاع أو ضبط نمط تقاطع الخطوط. قراءة/كتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**القيمة المرجعة:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

إرجاع أو ضبط نمط تقاطع الخطوط. قراءة/كتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

إرجاع أو ضبط حد القطع السميك للسطر. قراءة/كتابة float.

**القيمة المرجعة:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

إرجاع أو ضبط حد القطع السميك للسطر. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

إرجاع أو ضبط نمط رأس السهم في بداية السطر. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**القيمة المرجعة:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

إرجاع أو ضبط نمط رأس السهم في بداية السطر. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

إرجاع أو ضبط نمط رأس السهم في نهاية السطر. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**القيمة المرجعة:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

إرجاع أو ضبط نمط رأس السهم في نهاية السطر. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

إرجاع أو ضبط عرض رأس السهم في بداية السطر. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**القيمة المرجعة:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

إرجاع أو ضبط عرض رأس السهم في بداية السطر. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

إرجاع أو ضبط عرض رأس السهم في نهاية السطر. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**القيمة المرجعة:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

إرجاع أو ضبط عرض رأس السهم في نهاية السطر. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

إرجاع أو ضبط طول رأس السهم في بداية السطر. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**القيمة المرجعة:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

إرجاع أو ضبط طول رأس السهم في بداية السطر. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

إرجاع أو ضبط طول رأس السهم في نهاية السطر. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**القيمة المرجعة:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

إرجاع أو ضبط طول رأس السهم في نهاية السطر. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

تحديد ما إذا كانت مثيلات LineFormat اثنتان متساوية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | الـ LineFormat للمقارنة مع الـ LineFormat الحالي. |

**القيمة المرجعة:**  
boolean - **true** إذا كان الـ LineFormat المحدد مساويًا للـ LineFormat الحالي؛ وإلا **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

الحصول على بيانات تنسيق السطر الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).