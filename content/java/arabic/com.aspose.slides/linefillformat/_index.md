---
title: LineFillFormat
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل الخصائص لتعبئة الخطوط.
type: docs
url: /ar/com.aspose.slides/linefillformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

يمثل الخصائص لتعبئة الخطوط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | يعيد أو يضبط نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | يعيد أو يضبط نوع التعبئة. |
| [getRotateWithShape()](#getRotateWithShape--) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [getSolidFillColor()](#getSolidFillColor--) | يعيد لون تعبئة صلبة. |
| [getGradientFormat()](#getGradientFormat--) | يعيد تنسيق التعبئة المتدرجة. |
| [getPatternFormat()](#getPatternFormat--) | يعيد تنسيق تعبئة النمط. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. قراءة فقط long.

**الإرجاع:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


يعيد أو يضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


يعيد أو يضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


يعيد لون تعبئة صلبة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


يعيد تنسيق التعبئة المتدرجة. قراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**الإرجاع:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


يعيد تنسيق تعبئة النمط. قراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**الإرجاع:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)