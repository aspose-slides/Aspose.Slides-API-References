---
title: IFillFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خيارات تنسيق التعبئة.
type: docs
url: /ar/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

يمثل خيارات تنسيق التعبئة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | إرجاع أو ضبط نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | إرجاع أو ضبط نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | إرجاع لون التعبئة. |
| [getGradientFormat()](#getGradientFormat--) | إرجاع تنسيق تعبئة التدرج. |
| [getPatternFormat()](#getPatternFormat--) | إرجاع تنسيق تعبئة النمط. |
| [getPictureFillFormat()](#getPictureFillFormat--) | إرجاع تنسيق تعبئة الصورة. |
| [getRotateWithShape()](#getRotateWithShape--) | تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [getEffective()](#getEffective--) | الحصول على بيانات تنسيق التعبئة الفعّالة مع تطبيق الوراثة. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


إرجاع أو ضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


إرجاع أو ضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


إرجاع لون التعبئة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


إرجاع تنسيق تعبئة التدرج. قراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**الإرجاع:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


إرجاع تنسيق تعبئة النمط. قراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**الإرجاع:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


إرجاع تنسيق تعبئة الصورة. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


الحصول على بيانات تنسيق التعبئة الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).