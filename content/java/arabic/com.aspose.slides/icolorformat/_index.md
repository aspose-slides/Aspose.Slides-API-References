---
title: IColorFormat
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل لونًا يستخدم في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/icolorformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

يمثل لونًا يستخدم في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColorType()](#getColorType--) | إرجاع أو تعيين طريقة تعريف اللون. |
| [setColorType(int value)](#setColorType-int-) | إرجاع أو تعيين طريقة تعريف اللون. |
| [getColor()](#getColor--) | إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). |
| [setColor(Color value)](#setColor-java.awt.Color-) | إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). |
| [getPresetColor()](#getPresetColor--) | إرجاع أو تعيين إعداد اللون المسبق. |
| [setPresetColor(int value)](#setPresetColor-int-) | إرجاع أو تعيين إعداد اللون المسبق. |
| [getSystemColor()](#getSystemColor--) | إرجاع أو تعيين اللون المحدد من جدول ألوان النظام. |
| [setSystemColor(int value)](#setSystemColor-int-) | إرجاع أو تعيين اللون المحدد من جدول ألوان النظام. |
| [getSchemeColor()](#getSchemeColor--) | إرجاع أو تعيين اللون المحدد من مخطط ألوان. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | إرجاع أو تعيين اللون المحدد من مخطط ألوان. |
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
| [getHue()](#getHue--) | إرجاع أو تعيين المكوّن اللون (Hue) للون في تمثيل HSL. |
| [setHue(float value)](#setHue-float-) | إرجاع أو تعيين المكوّن اللون (Hue) للون في تمثيل HSL. |
| [getSaturation()](#getSaturation--) | إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. |
| [setSaturation(float value)](#setSaturation-float-) | إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. |
| [getLuminance()](#getLuminance--) | إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. |
| [setLuminance(float value)](#setLuminance-float-) | إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. |
| [getColorTransform()](#getColorTransform--) | إرجاع مجموعة تحويلات اللون المطبقة على لون. |
| [toString(int format)](#toString-int-) | إرجاع سلسلة تمثل تنسيق اللون الحالي. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | نسخ تنسيق اللون من "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

إرجاع أو تعيين طريقة تعريف اللون. قراءة/كتابة [ColorType](../../com.aspose.slides/colortype).

**الإرجاع:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

إرجاع أو تعيين طريقة تعريف اللون. قراءة/كتابة [ColorType](../../com.aspose.slides/colortype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). تعيين ألوان RGB وإزالة جميع تحويلات اللون. قراءة/كتابة java.awt.Color.

**الإرجاع:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

إرجاع اللون الناتج (مع تطبيق جميع تحويلات اللون). تعيين ألوان RGB وإزالة جميع تحويلات اللون. قراءة/كتابة java.awt.Color.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

إرجاع أو تعيين إعداد اللون المسبق. قراءة/كتابة [PresetColor](../../com.aspose.slides/presetcolor).

**الإرجاع:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

إرجاع أو تعيين إعداد اللون المسبق. قراءة/كتابة [PresetColor](../../com.aspose.slides/presetcolor).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

إرجاع أو تعيين اللون المحدد من جدول ألوان النظام. قراءة/كتابة [SystemColor](../../com.aspose.slides/systemcolor).

**الإرجاع:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

إرجاع أو تعيين اللون المحدد من جدول ألوان النظام. قراءة/كتابة [SystemColor](../../com.aspose.slides/systemcolor).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

إرجاع أو تعيين اللون المحدد من مخطط ألوان. قراءة/كتابة [SchemeColor](../../com.aspose.slides/schemecolor).

**الإرجاع:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

إرجاع أو تعيين اللون المحدد من مخطط ألوان. قراءة/كتابة [SchemeColor](../../com.aspose.slides/schemecolor).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

إرجاع أو تعيين المكوّن الأحمر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة byte.

**الإرجاع:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

إرجاع أو تعيين المكوّن الأحمر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

إرجاع أو تعيين المكوّن الأخضر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة byte.

**الإرجاع:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

إرجاع أو تعيين المكوّن الأخضر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

إرجاع أو تعيين المكوّن الأزرق للون. تُهمل جميع تحويلات اللون. قراءة/كتابة byte.

**الإرجاع:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

إرجاع أو تعيين المكوّن الأزرق للون. تُهمل جميع تحويلات اللون. قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

إرجاع أو تعيين المكوّن الأحمر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

إرجاع أو تعيين المكوّن الأحمر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

إرجاع أو تعيين المكوّن الأخضر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

إرجاع أو تعيين المكوّن الأخضر للون. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

إرجاع أو تعيين المكوّن الأزرق للون. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

إرجاع أو تعيين المكوّن الأزرق للون. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

إرجاع أو تعيين المكوّن اللون (Hue) للون في تمثيل HSL. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

إرجاع أو تعيين المكوّن اللون (Hue) للون في تمثيل HSL. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

إرجاع أو تعيين مكوّن التشبع للون في تمثيل HSL. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**الإرجاع:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

إرجاع أو تعيين مكوّن الإضاءة للون في تمثيل HSL. تُهمل جميع تحويلات اللون. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

إرجاع مجموعة تحويلات اللون المطبقة على لون. قراءة فقط [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**الإرجاع:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
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
public abstract void copyFrom(IColorFormat color)
```

نسخ تنسيق اللون من "color".

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | اللون [IColorFormat](../../com.aspose.slides/icolorformat) |