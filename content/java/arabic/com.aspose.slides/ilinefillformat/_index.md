---
title: ILineFillFormat
second_title: Aspose.Slides لمرجع API لجافا
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
| [getFillType()](#getFillType--) | يررج أو يضبط نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | يررج أو يضبط نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | يررج لون تعبئة صلبة. |
| [getGradientFormat()](#getGradientFormat--) | يررج تنسيق تعبئة التدرج. |
| [getPatternFormat()](#getPatternFormat--) | يررج تنسيق تعبئة النمط. |
| [getRotateWithShape()](#getRotateWithShape--) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

يررج أو يضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**القيمة المرجعة:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

يررج أو يضبط نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

يررج لون تعبئة صلبة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

يررج تنسيق تعبئة التدرج. قراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**القيمة المرجعة:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

يررج تنسيق تعبئة النمط. قراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**القيمة المرجعة:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | byte |  |