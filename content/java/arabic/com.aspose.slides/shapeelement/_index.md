---
title: ShapeElement
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل جزءًا من الشكل له نفس خصائص الحد والملء.
type: docs
url: /ar/com.aspose.slides/shapeelement/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

يمثل جزءًا من الشكل له نفس خصائص الحد والملء.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParentShape()](#getParentShape--) | إرجاع Shape_PPT التي تم إنشاء العنصر من أجلها. |
| [getPathPoints()](#getPathPoints--) | الحصول على مصفوفة من النقاط التي تحدد هندسة مسار العنصر. |
| [getPathTypes()](#getPathTypes--) | الحصول على مصفوفة من قيم البايت التي تحدد نوع كل نقطة في مسار العنصر. |
| [getFillSource()](#getFillSource--) | إرجاع معلومات حول كيفية تعبئة العنصر. |
| [getStrokeSource()](#getStrokeSource--) | إرجاع معلومات حول كيفية رسم حد للعنصر. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

إرجاع Shape_PPT التي تم إنشاء العنصر من أجلها. للقراءة فقط [Shape](../../com.aspose.slides/shape).

**الإرجاع:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

الحصول على مصفوفة من النقاط التي تحدد هندسة مسار العنصر.

**الإرجاع:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

الحصول على مصفوفة من قيم البايت التي تحدد نوع كل نقطة في مسار العنصر.

**0** يشير إلى أن النقطة هي بداية الشكل.

**1** يشير إلى أن النقطة هي أحد نقطتي النهاية لخط.

**3** يشير إلى أن النقطة هي نقطة نهاية أو نقطة تحكم لمنحنى بيزيه مكعب.

**7** يقنع جميع البتات باستثناء البتات الثلاثة ذات الأهمية الأقل، التي تحدد نوع النقطة.

**16** يحدد أن القطعة المقابلة منقطة.

**32** يحدد أن النقطة هي علامة.

**128** يحدد أن النقطة هي الأخيرة في مسار فرعي مغلق (شكل).

**129** يشير إلى نقطة بيانات هي كل من نقطة نهاية قطعة خطية والنقطة الأخيرة في مسار فرعي مغلق.

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

إرجاع معلومات حول كيفية رسم حد للعنصر. للقراءة فقط [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**الإرجاع:**
byte