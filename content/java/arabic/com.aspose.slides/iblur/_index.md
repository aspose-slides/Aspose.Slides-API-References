---
title: IBlur
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تأثير طمس يُطبق على الشكل بالكامل بما في ذلك تعبئته.
type: docs
url: /ar/com.aspose.slides/iblur/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

يمثل تأثير طمس يُطبق على الشكل بالكامل، بما في ذلك التعبئة. جميع قنوات اللون، بما في ذلك قناة ألفا، تتأثر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | إرجاع أو تعيين نصف القطر الضبابي. |
| [setRadius(double value)](#setRadius-double-) | إرجاع أو تعيين نصف القطر الضبابي. |
| [getGrow()](#getGrow--) | تحديد ما إذا كانت حدود الكائن يجب أن تتوسع نتيجةً للتمويه. |
| [setGrow(boolean value)](#setGrow-boolean-) | تحديد ما إذا كانت حدود الكائن يجب أن تتوسع نتيجةً للتمويه. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

إرجاع أو تعيين نصف القطر الضبابي. قراءة/كتابة double.

**القيمة المرجعة:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

إرجاع أو تعيين نصف القطر الضبابي. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

تحديد ما إذا كانت حدود الكائن يجب أن تتوسع نتيجةً للتمويه. القيم true تشير إلى أن الحدود تتوسع بينما false تشير إلى عدم ذلك. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

تحديد ما إذا كانت حدود الكائن يجب أن تتوسع نتيجةً للتمويه. القيم true تشير إلى أن الحدود تتوسع بينما false تشير إلى عدم ذلك. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |