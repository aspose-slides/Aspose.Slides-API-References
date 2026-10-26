---
title: ShapeFrame
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل خصائص إطارات الشكل.
type: docs
url: /ar/com.aspose.slides/shapeframe/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

يمثل خصائص إطار الشكل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | ينشئ خصائص إطار الشكل الجديد. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | يرجع الإحداثي X للزاوية العلوية اليسرى لإطار. |
| [getY()](#getY--) | يرجع الإحداثي Y للزاوية العلوية اليسرى لإطار. |
| [getWidth()](#getWidth--) | يرجع عرض الإطار. |
| [getHeight()](#getHeight--) | يرجع ارتفاع الإطار. |
| [getRotation()](#getRotation--) | يرجع عدد الدرجات التي يدور بها الإطار حول المحور z. |
| [getCenterX()](#getCenterX--) | يرجع إحداثي X لمركز الإطار. |
| [getCenterY()](#getCenterY--) | يرجع إحداثي Y لمركز الإطار. |
| [getFlipH()](#getFlipH--) | يحدد ما إذا كان الإطار مقلوبًا أفقياً. |
| [getFlipV()](#getFlipV--) | يحدد ما إذا كان الإطار مقلوبًا رأسياً. |
| [getRectangle()](#getRectangle--) | يرجع إحداثيات الإطار. |
| [deepClone()](#deepClone--) | ينسخ |
| [cloneT()](#cloneT--) | ينسخ. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه العينة مساوية لكائن محدد. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | يرجع قيمة تشير إلى ما إذا كانت هذه العينة مساوية لكائن محدد. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

ينشئ خصائص إطار الشكل الجديد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X لإطار. |
| y | float | إحداثي Y لإطار. |
| width | float | عرض الإطار. |
| height | float | ارتفاع الإطار. |
| flipH | byte | صحيح إذا كان الإطار مقلوبًا أفقياً. |
| flipV | byte | صحيح إذا كان الإطار مقلوبًا رأسياً. |
| rotationAngle | float | عدد الدرجات التي يدور بها الإطار. |
### getX() {#getX--}
```
public final float getX()
```

يرجع إحداثي X للزاوية العلوية اليسرى لإطار. للقراءة فقط float.

**الإرجاع:**
float
### getY() {#getY--}
```
public final float getY()
```

يرجع إحداثي Y للزاوية العلوية اليسرى لإطار. للقراءة فقط float.

**الإرجاع:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

يرجع عرض الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

يرجع ارتفاع الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

يرجع عدد الدرجات التي يدور بها الإطار حول المحور z. القيمة الإيجابية تدل على دوران باتجاه عقارب الساعة؛ القيمة السالبة تدل على دوران عكس اتجاهها. للقراءة فقط float.

**الإرجاع:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

يرجع إحداثي X لمركز الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

يرجع إحداثي Y لمركز الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

يحدد ما إذا كان الإطار مقلوبًا أفقياً. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

يحدد ما إذا كان الإطار مقلوبًا رأسياً. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

يرجع إحداثيات الإطار. للقراءة فقط java.awt.geom.Rectangle2D.Float.

**الإرجاع:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ينسخ

**الإرجاع:**
java.lang.Object - نسخة من إطار الشكل.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

ينسخ.

**الإرجاع:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - نسخة من إطار الشكل.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**الإرجاع:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يرجع قيمة تشير إلى ما إذا كانت هذه العينة مساوية لكائن محدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه العينة. |

**الإرجاع:**
boolean - **true** إذا كان obj هو ShapeFrame له نفس القيمة كهذه العينة؛ وإلا **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

يرجع قيمة تشير إلى ما إذا كانت هذه العينة مساوية لكائن محدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | الكائن ShapeFRameEx للمقارنة مع هذه العينة. |

**الإرجاع:**
boolean - **true** إذا كان value هو ShapeFrame له نفس القيمة كهذه العينة؛ وإلا **false**.