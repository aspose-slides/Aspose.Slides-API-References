---
title: ShapeFrame
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة تطبيقات Java
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

## المُنشئات

| Constructor | Description |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | ينشئ خصائص إطار شكل جديد. |

## الأساليب

| Method | Description |
| --- | --- |
| [getX()](#getX--) | يرجع إحداثي X للزاوية العلوية اليسرى للإطار. |
| [getY()](#getY--) | يرجع إحداثي Y للزاوية العلوية اليسرى للإطار. |
| [getWidth()](#getWidth--) | يرجع عرض الإطار. |
| [getHeight()](#getHeight--) | يرجع ارتفاع الإطار. |
| [getRotation()](#getRotation--) | يرجع عدد الدرجات التي يدور فيها الإطار حول المحور z. |
| [getCenterX()](#getCenterX--) | يرجع إحداثي X لمركز الإطار. |
| [getCenterY()](#getCenterY--) | يرجع إحداثي Y لمركز الإطار. |
| [getFlipH()](#getFlipH--) | يحدد ما إذا كان الإطار مقلوبًا أفقيًا. |
| [getFlipV()](#getFlipV--) | يحدد ما إذا كان الإطار مقلوبًا عموديًا. |
| [getRectangle()](#getRectangle--) | يرجع إحداثيات الإطار. |
| [deepClone()](#deepClone--) | ينسخ |
| [cloneT()](#cloneT--) | ينسخ. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لكائن محدد. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لكائن محدد. |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

ينشئ خصائص إطار شكل جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للإطار. |
| y | float | إحداثي Y للإطار. |
| width | float | عرض الإطار. |
| height | float | ارتفاع الإطار. |
| flipH | byte | صحيح إذا كان الإطار مقلوبًا أفقيًا. |
| flipV | byte | صحيح إذا كان الإطار مقلوبًا عموديًا. |
| rotationAngle | float | عدد الدرجات التي يدور فيها الإطار. |

### getX() {#getX--}
```
public final float getX()
```

يرجع إحداثي X للزاوية العلوية اليسرى للإطار. float للقراءة فقط.

**الإرجاع:**
float

### getY() {#getY--}
```
public final float getY()
```

يرجع إحداثي Y للزاوية العلوية اليسرى للإطار. float للقراءة فقط.

**الإرجاع:**
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

يرجع عرض الإطار. float للقراءة فقط.

**الإرجاع:**
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

يرجع ارتفاع الإطار. float للقراءة فقط.

**الإرجاع:**
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

يرجع عدد الدرجات التي يدور فيها الإطار حول المحور z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ والقيمة السالبة تدل على دوران عكس اتجاه عقارب الساعة. float للقراءة فقط.

**الإرجاع:**
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

يرجع إحداثي X لمركز الإطار. float للقراءة فقط.

**الإرجاع:**
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

يرجع إحداثي Y لمركز الإطار. float للقراءة فقط.

**الإرجاع:**
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

يحدد ما إذا كان الإطار مقلوبًا أفقيًا. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

يحدد ما إذا كان الإطار مقلوبًا عموديًا. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

يرجع إحداثيات الإطار. للقراءة فقط android.graphics.RectF.

**الإرجاع:**
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ينسخ

**الإرجاع:**
java.lang.Object - إطار الشكل المستنسخ.

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

ينسخ.

**الإرجاع:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - إطار الشكل المستنسخ.

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

يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لكائن محدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**الإرجاع:**
boolean - **true** إذا كان obj هو ShapeFrame له نفس القيمة كهذه الحالة؛ وإلا **false**.

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لكائن محدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx للمقارنة مع هذه الحالة. |

**الإرجاع:**
boolean - **true** إذا كان value هو ShapeFrame له نفس القيمة كهذه الحالة؛ وإلا **false**.