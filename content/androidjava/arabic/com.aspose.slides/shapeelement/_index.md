---
title: ShapeElement
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل جزءًا من الشكل له نفس خصائص الخط الخارجي والملء.
type: docs
url: /ar/com.aspose.slides/shapeelement/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

يمثل جزءًا من الشكل له نفس خصائص الخط الخارجي والملء.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getParentShape()](#getParentShape--) | إرجاع Shape_PPT الذي تم إنشاء العنصر من أجله. |
| [getPathPoints()](#getPathPoints--) | يحصل على مصفوفة من النقاط التي تحدد هندسة مسار العنصر. |
| [getPathTypes()](#getPathTypes--) | يحصل على مصفوفة من قيم البايت التي تحدد نوع كل نقطة في مسار العنصر. |
| [getFillSource()](#getFillSource--) | إرجاع معلومات حول كيفية تعبئة العنصر. |
| [getStrokeSource()](#getStrokeSource--) | إرجاع معلومات حول كيفية رسم حدود العنصر. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


إرجاع Shape_PPT الذي تم إنشاء العنصر من أجله. للقراءة فقط [Shape](../../com.aspose.slides/shape).

**الإرجاع:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```


يحصل على مصفوفة من النقاط التي تحدد هندسة مسار العنصر.

**الإرجاع:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


يحصل على مصفوفة من قيم البايت التي تحدد نوع كل نقطة في مسار العنصر.

**0** يشير إلى أن النقطة هي بداية الشكل.

**1** يشير إلى أن النقطة هي أحد نقطتي نهاية الخط.

**3** يشير إلى أن النقطة هي نقطة نهاية أو نقطة تحكم في منحنى بيزيه تكعيبي.

**7** يخفي جميع البتات باستثناء الثلاثة بتات الأقل ترتيبًا، والتي تشير إلى نوع النقطة.

**16** يحدد أن الجزء المقابل منقط.

**32** يحدد أن النقطة هي علامة.

**128** يحدد أن النقطة هي الأخيرة في مسار فرعي مغلق (شكل).

**129** يشير إلى نقطة بيانات هي كلًا من نقطة نهاية مقطع خط والنقطة الأخيرة في مسار فرعي مغلق.

**الإرجاع:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


إرجاع معلومات حول كيفية تعبئة العنصر. للقراءة فقط [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**الإرجاع:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


إرجاع معلومات حول كيفية رسم حدود العنصر. للقراءة فقط [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**الإرجاع:**
byte