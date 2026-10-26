---
title: IBlur
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل تأثير Blur يُطبق على الشكل بأكمله بما في ذلك التعبئة.
type: docs
url: /ar/com.aspose.slides/iblur/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

يمثل تأثير Blur يُطبق على الشكل بأكمله، بما في ذلك التعبئة. جميع قنوات اللون، بما فيها ألفا، متأثرة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | إرجاع أو تعيين نصف قطر الضبابية. |
| [setRadius(double value)](#setRadius-double-) | إرجاع أو تعيين نصف قطر الضبابية. |
| [getGrow()](#getGrow--) | يحدد ما إذا كان يجب توسيع حدود الكائن نتيجةً للتشويش. |
| [setGrow(boolean value)](#setGrow-boolean-) | يحدد ما إذا كان يجب توسيع حدود الكائن نتيجةً للتشويش. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


إرجاع أو تعيين نصف قطر الضبابية. قراءة/كتابة double.

**الإرجاع:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


إرجاع أو تعيين نصف قطر الضبابية. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


يحدد ما إذا كان يجب توسيع حدود الكائن نتيجة التشويش. القيمة True تشير إلى أن الحدود تم توسيعها بينما القيمة False تشير إلى أنها لم تُوسع. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


يحدد ما إذا كان يجب توسيع حدود الكائن نتيجة التشويش. القيمة True تشير إلى أن الحدود تم توسيعها بينما القيمة False تشير إلى أنها لم تُوسع. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |