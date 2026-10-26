---
title: IColorFormat
second_title: Aspose.Slides للـ Android عبر مرجع API Java
description: يمثل لونًا يُستخدم في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/icolorformat/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

يمثل لونًا يستخدم في عرض تقديمي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorType()](#getColorType--) | يُرجِع أو يُعيِّن طريقة تعريف اللون. |
| [setColorType(int value)](#setColorType-int-) | يُرجِع أو يُعيِّن طريقة تعريف اللون. |
| [getColor()](#getColor--) | يُرجِع اللون الناتج (مع تطبيق جميع تحولات اللون). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | يُرجِع اللون الناتج (مع تطبيق جميع تحولات اللون). |
| [getPresetColor()](#getPresetColor--) | يُرجِع أو يُعيِّن إعداد اللون المسبق. |
| [setPresetColor(int value)](#setPresetColor-int-) | يُرجِع أو يُعيِّن إعداد اللون المسبق. |
| [getSystemColor()](#getSystemColor--) | يُرجِع أو يُعيِّن اللون المحدد بواسطة جدول ألوان النظام. |
| [setSystemColor(int value)](#setSystemColor-int-) | يُرجِع أو يُعيِّن اللون المحدد بواسطة جدول ألوان النظام. |
| [getSchemeColor()](#getSchemeColor--) | يُرجِع أو يُعيِّن اللون المحدد بواسطة نظام ألوان. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | يُرجِع أو يُعيِّن اللون المحدد بواسطة نظام ألوان. |
| [getR()](#getR--) | يُرجِع أو يُعيِّن المكوّن الأحمر للون. |
| [setR(byte value)](#setR-byte-) | يُرجِع أو يُعيِّن المكوّن الأحمر للون. |
| [getG()](#getG--) | يُرجِع أو يُعيِّن المكوّن الأخضر للون. |
| [setG(byte value)](#setG-byte-) | يُرجِع أو يُعيِّن المكوّن الأخضر للون. |
| [getB()](#getB--) | يُرجِع أو يُعيِّن المكوّن الأزرق للون. |
| [setB(byte value)](#setB-byte-) | يُرجِع أو يُعيِّن المكوّن الأزرق للون. |
| [getFloatR()](#getFloatR--) | يُرجِع أو يُعيِّن المكوّن الأحمر للون. |
| [setFloatR(float value)](#setFloatR-float-) | يُرجِع أو يُعيِّن المكوّن الأحمر للون. |
| [getFloatG()](#getFloatG--) | يُرجِع أو يُعيِّن المكوّن الأخضر للون. |
| [setFloatG(float value)](#setFloatG-float-) | يُرجِع أو يُعيِّن المكوّن الأخضر للون. |
| [getFloatB()](#getFloatB--) | يُرجِع أو يُعيِّن المكوّن الأزرق للون. |
| [setFloatB(float value)](#setFloatB-float-) | يُرجِع أو يُعيِّن المكوّن الأزرق للون. |
| [getHue()](#getHue--) | يُرجِع أو يُعيِّن مكوّن الصبغة للون في تمثيل HSL. |
| [setHue(float value)](#setHue-float-) | يُرجِع أو يُعيِّن مكوّن الصبغة للون في تمثيل HSL. |
| [getSaturation()](#getSaturation--) | يُرجِع أو يُعيِّن مكوّن الإشباع للون في تمثيل HSL. |
| [setSaturation(float value)](#setSaturation-float-) | يُرجِع أو يُعيِّن مكوّن الإشباع للون في تمثيل HSL. |
| [getLuminance()](#getLuminance--) | يُرجِع أو يُعيِّن مكوّن الإضاءة للون في تمثيل HSL. |
| [setLuminance(float value)](#setLuminance-float-) | يُرجِع أو يُعيِّن مكوّن الإضاءة لللون في تمثيل HSL. |
| [getColorTransform()](#getColorTransform--) | يُرجِع مجموعة تحولات اللون المطبقة على اللون. |
| [toString(int format)](#toString-int-) | يُرجِع سلسلة تمثّل تنسيق اللون الحالي. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | انسخ تنسيق اللون من "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

يُرجِع أو يُعيِّن طريقة تعريف اللون. قراءة/كتابة [ColorType](../../com.aspose.slides/colortype).

**الإرجاع:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

يُرجِع أو يُعيِّن طريقة تعريف اللون. قراءة/كتابة [ColorType](../../com.aspose.slides/colortype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

يُرجِع اللون الناتج (مع تطبيق جميع تحولات اللون). يُعيّن ألوان RGB ويُزيل جميع تحولات اللون. قراءة/كتابة java.lang.Integer.

**الإرجاع:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

يُرجِع اللون الناتج (مع تطبيق جميع تحولات اللون). يُعيّن ألوان RGB ويُزيل جميع تحولات اللون. قراءة/كتابة java.lang.Integer.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

يُرجِع أو يُعيِّن إعداد اللون المسبق. قراءة/كتابة [PresetColor](../../com.aspose.slides/presetcolor).

**الإرجاع:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

يُرجِع أو يُعيِّن إعداد اللون المسبق. قراءة/كتابة [PresetColor](../../com.aspose.slides/presetcolor).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

يُرجِع أو يُعيِّن اللون المحدد بواسطة جدول ألوان النظام. قراءة/كتابة [SystemColor](../../com.aspose.slides/systemcolor).

**الإرجاع:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

يُرجِع أو يُعيِّن اللون المحدد بواسطة جدول ألوان النظام. قراءة/كتابة [SystemColor](../../com.aspose.slides/systemcolor).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

يُرجِع أو يُعيِّن اللون المحدد بواسطة نظام ألوان. قراءة/كتابة [SchemeColor](../../com.aspose.slides/schemecolor).

**الإرجاع:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

يُرجِع أو يُعيِّن اللون المحدد بواسطة نظام ألوان. قراءة/كتابة [SchemeColor](../../com.aspose.slides/schemecolor).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

يُرجِع أو يُعيِّن المكوّن الأحمر للون. تُهمل جميع تحولات اللون. قراءة/كتابة byte.

**الإرجاع:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

يُرجِع أو يُعيِّن المكوّن الأحمر للون. تُهمل جميع تحولات اللون. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

يُرجِع أو يُعيِّن المكوّن الأخضر للون. تُهمل جميع تحولات اللون. قراءة/كتابة byte.

**الإرجاع:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

يُرجِع أو يُعيِّن المكوّن الأخضر للون. تُهمل جميع تحولات اللون. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

يُرجِع أو يُعيِّن المكوّن الأزرق للون. تُهمل جميع تحولات اللون. قراءة/كتابة byte.

**الإرجاع:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

يُرجِع أو يُعيِّن المكوّن الأزرق للون. تُهمل جميع تحولات اللون. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

يُرجِع أو يُعيِّن المكوّن الأحمر للون. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

يُرجِع أو يُعيِّن المكوّن الأحمر للون. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

يُرجِع أو يُعيِّن المكوّن الأخضر للون. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

يُرجِع أو يُعيِّن المكوّن الأخضر للون. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

يُرجِع أو يُعيِّن المكوّن الأزرق للون. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

يُرجِع أو يُعيِّن المكوّن الأزرق للون. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

يُرجِع أو يُعيِّن مكوّن الصبغة للون في تمثيل HSL. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

يُرجِع أو يُعيِّن مكوّن الصبغة للون في تمثيل HSL. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

يُرجِع أو يُعيِّن مكوّن الإشباع للون في تمثيل HSL. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

يُرجِع أو يُعيِّن مكوّن الإشباع للون في تمثيل HSL. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

يُرجِع أو يُعيِّن مكوّن الإضاءة للون في تمثيل HSL. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

يُرجِع أو يُعيِّن مكوّن الإضاءة للون في تمثيل HSL. تُهمل جميع تحولات اللون. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

يُرجِع مجموعة تحولات اللون المطبقة على اللون. قراءة فقط [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**الإرجاع:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

يُرجِع سلسلة تمثّل تنسيق اللون الحالي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| format | int | نوع تنسيق سلسلة اللون. |

**الإرجاع:**
java.lang.String - سلسلة تمثّل تنسيق اللون الحالي.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

انسخ تنسيق اللون من "color".

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | لون [IColorFormat](../../com.aspose.slides/icolorformat) |