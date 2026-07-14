---
title: IGlow
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل تأثير توهج يتم فيه إضافة حدود ملونة مشوشة خارج حواف الكائن.
type: docs
url: /ar/com.aspose.slides/iglow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

يمثل تأثير توهج، حيث يتم إضافة حد ملون مشوّش خارج حواف الكائن.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
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

**المعاملات:**
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