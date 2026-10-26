---
title: LineFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تنسيق الخط.
type: docs
url: /ar/com.aspose.slides/lineformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)  
```
public final class LineFormat extends PVIObject implements ILineFormat
```

يمثل تنسيق الخط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | يعيد true إذا لم يتم تعريف تنسيق الخط (كما تم إنشاؤه حديثًا، افتراضي). |
| [getFillFormat()](#getFillFormat--) | يعيد تنسيق التعبئة للخط. |
| [getSketchFormat()](#getSketchFormat--) | يعيد تنسيق الرسم للخط. |
| [getWidth()](#getWidth--) | يعيد أو يحدد عرض الخط. |
| [setWidth(double value)](#setWidth-double-) | يعيد أو يحدد عرض الخط. |
| [getDashStyle()](#getDashStyle--) | يعيد أو يحدد نمط شرطة الخط. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | يعيد أو يحدد نمط شرطة الخط. |
| [getCustomDashPattern()](#getCustomDashPattern--) | يعيد أو يحدد نمط الشرط المخصص. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | يعيد أو يحدد نمط الشرط المخصص. |
| [getCapStyle()](#getCapStyle--) | يعيد أو يحدد نمط طرف الخط. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | يعيد أو يحدد نمط طرف الخط. |
| [getStyle()](#getStyle--) | يعيد أو يحدد نمط الخط. |
| [setStyle(byte value)](#setStyle-byte-) | يعيد أو يحدد نمط الخط. |
| [getAlignment()](#getAlignment--) | يعيد أو يحدد محاذاة الخط. |
| [setAlignment(byte value)](#setAlignment-byte-) | يعيد أو يحدد محاذاة الخط. |
| [getJoinStyle()](#getJoinStyle--) | يعيد أو يحدد نمط وصل الخطوط. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | يعيد أو يحدد نمط وصل الخطوط. |
| [getMiterLimit()](#getMiterLimit--) | يعيد أو يحدد حد الميل للخط. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | يعيد أو يحدد حد الميل للخط. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | يعيد أو يحدد نمط رأس السهم في بداية الخط. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | يعيد أو يحدد نمط رأس السهم في بداية الخط. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | يعيد أو يحدد نمط رأس السهم في نهاية الخط. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | يعيد أو يحدد نمط رأس السهم في نهاية الخط. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | يعيد أو يحدد عرض رأس السهم في بداية الخط. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | يعيد أو يحدد عرض رأس السهم في بداية الخط. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | يعيد أو يحدد عرض رأس السهم في نهاية الخط. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | يعيد أو يحدد عرض رأس السهم في نهاية الخط. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | يعيد أو يحدد طول رأس السهم في بداية الخط. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | يعيد أو يحدد طول رأس السهم في بداية الخط. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | يعيد أو يحدد طول رأس السهم في نهاية الخط. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | يعيد أو يحدد طول رأس السهم في نهاية الخط. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | يحدد ما إذا كانت مثيلات LineFormat الاثنين متساوية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الخط الفعال مع تطبيق الوراثة. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**إرجاع:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يقارن مع الكائن المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**إرجاع:**  
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

يعيد true إذا لم يتم تعريف تنسيق الخط (كما تم إنشاؤه حديثًا، افتراضي). قراءة فقط boolean .

**إرجاع:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

يعيد تنسيق التعبئة للخط. قراءة فقط [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**إرجاع:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

يعيد تنسيق الرسم للخط. قراءة فقط [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**إرجاع:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

يعيد أو يحدد عرض الخط. قراءة/كتابة  double .

**إرجاع:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

يعيد أو يحدد عرض الخط. قراءة/كتابة  double .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

يعيد أو يحدد نمط شرطة الخط. قراءة/كتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**إرجاع:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

يعيد أو يحدد نمط شرطة الخط. قراءة/كتابة [LineDashStyle](../../com.aspose.slides/linedashstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

يعيد أو يحدد نمط الشرط المخصص. قراءة/كتابة  float[] .

**إرجاع:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

يعيد أو يحدد نمط الشرط المخصص. قراءة/كتابة  float[] .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

يعيد أو يحدد نمط طرف الخط. قراءة/كتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**إرجاع:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

يعيد أو يحدد نمط طرف الخط. قراءة/كتابة [LineCapStyle](../../com.aspose.slides/linecapstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

يعيد أو يحدد نمط الخط. قراءة/كتابة [LineStyle](../../com.aspose.slides/linestyle).

**إرجاع:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

يعيد أو يحدد نمط الخط. قراءة/كتابة [LineStyle](../../com.aspose.slides/linestyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

يعيد أو يحدد محاذاة الخط. قراءة/كتابة [LineAlignment](../../com.aspose.slides/linealignment).

**إرجاع:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

يعيد أو يحدد محاذاة الخط. قراءة/كتابة [LineAlignment](../../com.aspose.slides/linealignment).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

يعيد أو يحدد نمط وصل الخطوط. قراءة/كتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**إرجاع:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

يعيد أو يحدد نمط وصل الخطوط. قراءة/كتابة [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

يعيد أو يحدد حد الميل للخط. قراءة/كتابة  float .

**إرجاع:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

يعيد أو يحدد حد الميل للخط. قراءة/كتابة  float .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

يعيد أو يحدد نمط رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**إرجاع:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

يعيد أو يحدد نمط رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

يعيد أو يحدد نمط رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**إرجاع:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

يعيد أو يحدد نمط رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

يعيد أو يحدد عرض رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**إرجاع:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

يعيد أو يحدد عرض رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

يعيد أو يحدد عرض رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**إرجاع:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

يعيد أو يحدد عرض رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

يعيد أو يحدد طول رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**إرجاع:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

يعيد أو يحدد طول رأس السهم في بداية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

يعيد أو يحدد طول رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**إرجاع:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

يعيد أو يحدد طول رأس السهم في نهاية الخط. قراءة/كتابة [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

يحدد ما إذا كانت مثيلات LineFormat الاثنين متساوية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | الـ LineFormat للمقارنة مع الـ LineFormat الحالي. |

**إرجاع:**  
boolean - **true** إذا كان الـ LineFormat المحدد متساويًا مع الـ LineFormat الحالي؛ غير ذلك **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الخط الفعال مع تطبيق الوراثة.

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


**إرجاع:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).