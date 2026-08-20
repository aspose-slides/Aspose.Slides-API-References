---
title: IGlow
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل تأثير توهج يتم فيه إضافة حد ملون مضبّب خارج حواف الكائن.
type: docs
url: /ar/com.aspose.slides/iglow/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

يمثل تأثير توهج، حيث يتم إضافة حد ملون مضبّب خارج حواف الكائن.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | نصف القطر. |
| [setRadius(double value)](#setRadius-double-) | نصف القطر. |
| [getColor()](#getColor--) | تنسيق اللون. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


نصف القطر. قراءة/كتابة double.

**الإرجاع:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


نصف القطر. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


تنسيق اللون. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)