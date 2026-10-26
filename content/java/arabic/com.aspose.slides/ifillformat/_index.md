---
title: IFillFormat
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل خيارات تنسيق التعبئة.
type: docs
url: /ar/com.aspose.slides/ifillformat/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

يمثل خيارات تنسيق التعبئة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | يعيد أو يضبط نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | يعيد أو يضبط نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | يعيد لون التعبئة. |
| [getGradientFormat()](#getGradientFormat--) | يعيد تنسيق التعبئة المتدرج. |
| [getPatternFormat()](#getPatternFormat--) | يعيد تنسيق تعبئة النمط. |
| [getPictureFillFormat()](#getPictureFillFormat--) | يعيد تنسيق تعبئة الصورة. |
| [getRotateWithShape()](#getRotateWithShape--) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق التعبئة الفعّالة مع تطبيق الوراثة. |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

يعيد أو يضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

يعيد أو يضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

يعيد لون التعبئة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

يعيد تنسيق التعبئة المتدرج. قراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**الإرجاع:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

يعيد تنسيق تعبئة النمط. قراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**الإرجاع:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

يعيد تنسيق تعبئة الصورة. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق التعبئة الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).