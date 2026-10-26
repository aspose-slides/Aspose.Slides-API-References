---
title: ILineFillFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خصائص تعبئة الخطوط.
type: docs
url: /ar/com.aspose.slides/ilinefillformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

يمثل خصائص تعبئة الخطوط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | إرجاع أو تعيين نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | إرجاع أو تعيين نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | إرجاع لون التعبئة الصلبة. |
| [getGradientFormat()](#getGradientFormat--) | إرجاع تنسيق تعبئة التدرج. |
| [getPatternFormat()](#getPatternFormat--) | إرجاع تنسيق تعبئة النمط. |
| [getRotateWithShape()](#getRotateWithShape--) | تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

إرجاع أو تعيين نوع التعبئة. قابل للقراءة والكتابة [FillType](../../com.aspose.slides/filltype).

**القيمة المرجعة:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

إرجاع أو تعيين نوع التعبئة. قابل للقراءة والكتابة [FillType](../../com.aspose.slides/filltype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

إرجاع لون التعبئة الصلبة. قابل للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

إرجاع تنسيق تعبئة التدرج. قابل للقراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**القيمة المرجعة:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

إرجاع تنسيق تعبئة النمط. قابل للقراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**القيمة المرجعة:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

تحديد ما إذا كان يجب تدوير التعبئة مع الشكل. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |