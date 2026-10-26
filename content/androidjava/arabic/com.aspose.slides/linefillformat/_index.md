---
title: LineFillFormat
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل خصائص تعبئة الخطوط.
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

يمثل خصائص تعبئة الخطوط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | إرجاع أو ضبط نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | إرجاع أو ضبط نوع التعبئة. |
| [getRotateWithShape()](#getRotateWithShape--) | تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [getSolidFillColor()](#getSolidFillColor--) | إرجاع لون التعبئة الصلبة. |
| [getGradientFormat()](#getGradientFormat--) | إرجاع تنسيق التعبئة المتدرجة. |
| [getPatternFormat()](#getPatternFormat--) | إرجاع تنسيق تعبئة النمط. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. للقراءة فقط long.

**الإرجاع:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


إرجاع أو ضبط نوع التعبئة. للقراءة والكتابة [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


إرجاع أو ضبط نوع التعبئة. للقراءة والكتابة [FillType](../../com.aspose.slides/filltype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


إرجاع لون التعبئة الصلبة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


إرجاع تنسيق التعبئة المتدرجة. للقراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**الإرجاع:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


إرجاع تنسيق تعبئة النمط. للقراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**الإرجاع:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)