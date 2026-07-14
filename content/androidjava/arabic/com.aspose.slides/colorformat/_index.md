---
title: ColorFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل لونًا يُستخدم في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/colorformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المطبقة:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

يمثل لونًا يُستخدم في العرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColorType()](#getColorType--) | إرجاع أو تعيين طريقة تعريف اللون. |
| [setColorType(int value)](#setColorType-int-) | إرجاع أو تعيين طريقة تعريف اللون. |
| [getColor()](#getColor--) | إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). |
| [getPresetColor()](#getPresetColor--) | إرجاع أو تعيين إعداد اللون المسبق. |
| [setPresetColor(int value)](#setPresetColor-int-) | إرجاع أو تعيين إعداد اللون المسبق. |
| [getSystemColor()](#getSystemColor--) | إرجاع أو تعيين اللون المحدد بواسطة جدول ألوان النظام. |
| [setSystemColor(int value)](#setSystemColor-int-) | إرجاع أو تعيين اللون المحدد بواسطة جدول ألوان النظام. |
| [getSchemeColor()](#getSchemeColor--) | إرجاع أو تعيين اللون المحدد بواسطة نظام ألوان. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | إرجاع أو تعيين اللون المحدد بواسطة نظام ألوان. |
| [getR()](#getR--) | إرجاع أو تعيين المكوّن الأحمر للون. |
| [setR(byte value)](#setR-byte-) | إرجاع أو تعيين المكوّن الأحمر للون. |
| [getG()](#getG--) | إرجاع أو تعيين المكوّن الأخضر للون. |
| [setG(byte value)](#setG-byte-) | إرجاع أو تعيين المكوّن الأخضر للون. |
| [getB()](#getB--) | إرجاع أو تعيين المكوّن الأزرق للون. |
| [setB(byte value)](#setB-byte-) | إرجاع أو تعيين المكوّن الأزرق للون. |
| [getFloatR()](#getFloatR--) | إرجاع أو تعيين المكوّن الأحمر للون. |
| [setFloatR(float value)](#setFloatR-float-) | إرجاع أو تعيين المكوّن الأحمر للون. |
| [getFloatG()](#getFloatG--) | إرجاع أو تعيين المكوّن الأخضر للون. |
| [setFloatG(float value)](#setFloatG-float-) | إرجاع أو تعيين المكوّن الأخضر للون. |
| [getFloatB()](#getFloatB--) | إرجاع أو تعيين المكوّن الأزرق للون. |
| [setFloatB(float value)](#setFloatB-float-) | إرجاع أو تعيين المكوّن الأزرق للون. |
| [getHue()](#getHue--) | إرجاع أو تعيين مكوّن الصبغة للون في تمثيل HSL. |
| [setHue(float value)](#setHue-float-) | إرجاع أو تعيين مكوّن الصبغة للون في تمثيل HSL. |
| [getSaturation()](#getSaturation--) | إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. |
| [setSaturation(float value)](#setSaturation-float-) | إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. |
| [getLuminance()](#getLuminance--) | إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. |
| [setLuminance(float value)](#setLuminance-float-) | إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. |
| [getColorTransform()](#getColorTransform--) | إرجاع مجموعة تحويلات اللون المطبقة على اللون. |
| [toString(int format)](#toString-int-) | إرجاع سلسلة تمثل تنسيق اللون الحالي. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | نسخ تنسيق اللون من "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | التحقق من المساواة مع الكائن المحدد Object. |
| [hashCode()](#hashCode--) | إرجاع رمز التجزئة. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

إرجاع أو تعيين طريقة تعريف اللون. قراءة/كتابة [ColorType](../../com.aspose.slides/colortype).

**الإرجاع:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

إرجاع أو تعيين طريقة تعريف اللون. قراءة/كتابة [ColorType](../../com.aspose.slides/colortype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). تعيين ألوان RGB وإزالة جميع تحويلات اللون. قراءة/كتابة java.lang.Integer.

**الإرجاع:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). تعيين ألوان RGB وإزالة جميع تحويلات اللون. قراءة/كتابة java.lang.Integer.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

إرجاع أو تعيين إعداد اللون المسبق. قراءة/كتابة [PresetColor](../../com.aspose.slides/presetcolor).

**الإرجاع:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

إرجاع أو تعيين إعداد اللون المسبق. قراءة/كتابة [PresetColor](../../com.aspose.slides/presetcolor).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

إرجاع أو تعيين اللون المحدد بواسطة جدول ألوان النظام. قراءة/كتابة [SystemColor](../../com.aspose.slides/systemcolor).

**الإرجاع:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

إرجاع أو تعيين اللون المحدد بواسطة جدول ألوان النظام. قراءة/كتابة [SystemColor](../../com.aspose.slides/systemcolor).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

إرجاع أو تعيين اللون المحدد بواسطة نظام ألوان. قراءة/كتابة [SchemeColor](../../com.aspose.slides/schemecolor).

**الإرجاع:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

إرجاع أو تعيين اللون المحدد بواسطة نظام ألوان. قراءة/كتابة [SchemeColor](../../com.aspose.slides/schemecolor).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

إرجاع أو تعيين المكوّن الأحمر للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة byte .

**الإرجاع:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

إرجاع أو تعيين المكوّن الأحمر للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة byte .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

إرجاع أو تعيين المكوّن الأخضر للون. جميع تحويلات اللون تُتجاهل.

**الإرجاع:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

إرجاع أو تعيين المكوّن الأخضر للون. جميع تحويلات اللون تُتجاهل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

إرجاع أو تعيين المكوّن الأزرق للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة byte .

**الإرجاع:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

إرجاع أو تعيين المكوّن الأزرق للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة byte .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

إرجاع أو تعيين المكوّن الأحمر للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**الإرجاع:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

إرجاع أو تعيين المكوّن الأحمر للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

إرجاع أو تعيين المكوّن الأخضر للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**الإرجاع:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

إرجاع أو تعيين المكوّن الأخضر للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

إرجاع أو تعيين المكوّن الأزرق للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**الإرجاع:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

إرجاع أو تعيين المكوّن الأزرق للون. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

إرجاع أو تعيين مكوّن الصبغة للون في تمثيل HSL. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**الإرجاع:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

إرجاع أو تعيين مكوّن الصبغة للون في تمثيل HSL. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**الإرجاع:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**الإرجاع:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. جميع تحويلات اللون تُتجاهل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

إرجاع مجموعة تحويلات اللون المطبقة على اللون. قراءة فقط [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**الإرجاع:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

إرجاع سلسلة تمثل تنسيق اللون الحالي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | int | نوع تنسيق سلسلة اللون. |

**الإرجاع:**
java.lang.String - سلسلة تمثل تنسيق اللون الحالي.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

نسخ تنسيق اللون من "color".

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

التحقق من المساواة مع الكائن المحدد Object.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن. |

**الإرجاع:**
boolean - True إذا كانت الكائنات متساوية، وإلا false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

إرجاع رمز التجزئة.

**الإرجاع:**
int - رمز التجزئة.

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```




**الإرجاع:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

إرجاع العنصر الأب IPresentationComponent. قراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)