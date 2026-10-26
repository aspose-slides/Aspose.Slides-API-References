---
title: LineFormat
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل تنسيق سطر.
type: docs
url: /ar/com.aspose.slides/lineformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)  
```
public final class LineFormat extends PVIObject implements ILineFormat
```

يمثل تنسيق سطر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | إرجاع true إذا لم يتم تعريف تنسيق السطر (كما تم إنشاؤه حديثًا، الافتراضي). |
| [getFillFormat()](#getFillFormat--) | إرجاع تنسيق التعبئة للسطر. |
| [getSketchFormat()](#getSketchFormat--) | إرجاع تنسيق التخطيط للسطر. |
| [getWidth()](#getWidth--) | إرجاع أو تعيين عرض السطر. |
| [setWidth(double value)](#setWidth-double-) | إرجاع أو تعيين عرض السطر. |
| [getDashStyle()](#getDashStyle--) | إرجاع أو تعيين نمط الخط المتقطع. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | إرجاع أو تعيين نمط الخط المتقطع. |
| [getCustomDashPattern()](#getCustomDashPattern--) | إرجاع أو تعيين نمط الخط المتقطع المخصص. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | إرجاع أو تعيين نمط الخط المتقطع المخصص. |
| [getCapStyle()](#getCapStyle--) | إرجاع أو تعيين نمط قمة الخط. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | إرجاع أو تعيين نمط قمة الخط. |
| [getStyle()](#getStyle--) | إرجاع أو تعيين نمط الخط. |
| [setStyle(byte value)](#setStyle-byte-) | إرجاع أو تعيين نمط الخط. |
| [getAlignment()](#getAlignment--) | إرجاع أو تعيين محاذاة الخط. |
| [setAlignment(byte value)](#setAlignment-byte-) | إرجاع أو تعيين محاذاة الخط. |
| [getJoinStyle()](#getJoinStyle--) | إرجاع أو تعيين نمط تقاطع الخطوط. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | إرجاع أو تعيين نمط تقاطع الخطوط. |
| [getMiterLimit()](#getMiterLimit--) | إرجاع أو تعيين حد الميتر لخط. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | إرجاع أو تعيين حد الميتر لخط. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | إرجاع أو تعيين نمط رأس السهم في بداية الخط. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | إرجاع أو تعيين نمط رأس السهم في بداية الخط. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | إرجاع أو تعيين نمط رأس السهم في نهاية الخط. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | إرجاع أو تعيين نمط رأس السهم في نهاية الخط. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | إرجاع أو تعيين عرض رأس السهم في بداية الخط. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | إرجاع أو تعيين عرض رأس السهم في بداية الخط. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | إرجاع أو تعيين عرض رأس السهم في نهاية الخط. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | إرجاع أو تعيين عرض رأس السهم في نهاية الخط. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | إرجاع أو تعيين طول رأس السهم في بداية الخط. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | إرجاع أو تعيين طول رأس السهم في بداية الخط. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | إرجاع أو تعيين طول رأس السهم في نهاية الخط. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | إرجاع أو تعيين طول رأس السهم في نهاية الخط. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | تحديد ما إذا كان مثالي LineFormat متساويين. |
| [getEffective()](#getEffective--) | الحصول على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يقارن مع الكائن المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**الإرجاع:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

إرجاع true إذا لم يتم تعريف تنسيق السطر (كما تم إنشاؤه حديثًا، الافتراضي). قراءة فقط boolean.

**الإرجاع:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

إرجاع تنسيق التعبئة لسطر. قراءة فقط [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**الإرجاع:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

إرجاع تنسيق التخطيط لسطر. قراءة فقط [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**الإرجاع:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

إرجاع أو تعيين عرض السطر. قراءة/كتابة double.

**الإرجاع:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

إرجاع أو تعيين عرض السطر. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

إرجاع أو تعيين نمط الخط المتقطع. قراءة/كتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**الإرجاع:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

إرجاع أو تعيين نمط الخط المتقطع. قراءة/كتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

إرجاع أو تعيين نمط الخط المتقطع المخصص. قراءة/كتابة float[].

**الإرجاع:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

إرجاع أو تعيين نمط الخط المتقطع المخصص. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

إرجاع أو تعيين نمط قمة الخط. قراءة/كتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**الإرجاع:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

إرجاع أو تعيين نمط قمة الخط. قراءة/كتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

إرجاع أو تعيين نمط الخط. قراءة/كتابة [LineStyle](../../com.aspose.slides/linestyle).

**الإرجاع:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

إرجاع أو تعيين نمط الخط. قراءة/كتابة [LineStyle](../../com.aspose.slides/linestyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

إرجاع أو تعيين محاذاة الخط. قراءة/كتابة [LineAlignment](../../com.aspose.slides/linealignment).

**الإرجاع:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

إرجاع أو تعيين محاذاة الخط. قراءة/كتابة [LineAlignment](../../com.aspose.slides/linealignment).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

إرجاع أو تعيين نمط تقاطع الخطوط. قراءة/كتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**الإرجاع:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

إرجاع أو تعيين نمط تقاطع الخطوط. قراءة/كتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

إرجاع أو تعيين حد الميتر لخط. قراءة/كتابة float.

**الإرجاع:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

إرجاع أو تعيين حد الميتر لخط. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

إرجاع أو تعيين نمط رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**الإرجاع:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

إرجاع أو تعيين نمط رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

إرجاع أو تعيين نمط رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**الإرجاع:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

إرجاع أو تعيين نمط رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

إرجاع أو تعيين عرض رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**الإرجاع:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

إرجاع أو تعيين عرض رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

إرجاع أو تعيين عرض رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**الإرجاع:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

إرجاع أو تعيين عرض رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

إرجاع أو تعيين طول رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**الإرجاع:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

إرجاع أو تعيين طول رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

إرجاع أو تعيين طول رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**الإرجاع:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

إرجاع أو تعيين طول رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

تحديد ما إذا كان مثالي LineFormat متساويين.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | الـ LineFormat للمقارنة مع الـ LineFormat الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الـ LineFormat المحدد متساويًا مع الـ LineFormat الحالي؛ وإلا **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

الحصول على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).