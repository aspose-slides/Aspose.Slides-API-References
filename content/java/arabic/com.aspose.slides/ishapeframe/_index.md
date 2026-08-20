---
title: IShapeFrame
second_title: مرجع API Aspose.Slides for Java
description: يمثل خصائص إطارات الشكل.
type: docs
url: /ar/com.aspose.slides/ishapeframe/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

يمثل خصائص إطار الشكل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | يرجع إحداثي X للزاوية العليا اليسرى للإطار. |
| [getY()](#getY--) | يرجع إحداثي Y للزاوية العليا اليسرى للإطار. |
| [getWidth()](#getWidth--) | يرجع عرض الإطار. |
| [getHeight()](#getHeight--) | يرجع ارتفاع الإطار. |
| [getRotation()](#getRotation--) | يرجع عدد الدرجات التي يدور فيها الإطار حول محور Z. |
| [getCenterX()](#getCenterX--) | يرجع إحداثي X لمركز الإطار. |
| [getCenterY()](#getCenterY--) | يرجع إحداثي Y لمركز الإطار. |
| [getFlipH()](#getFlipH--) | يحدد ما إذا كان الإطار مقلوبًا أفقيًا. |
| [getFlipV()](#getFlipV--) | يحدد ما إذا كان الإطار مقلوبًا عموديًا. |
| [getRectangle()](#getRectangle--) | يرجع إحداثيات الإطار. |
### getX() {#getX--}
```
public abstract float getX()
```

يرجع إحداثي X للزاوية العليا اليسرى للإطار. للقراءة فقط float.

**الإرجاع:**
float
### getY() {#getY--}
```
public abstract float getY()
```

يرجع إحداثي Y للزاوية العليا اليسرى للإطار. للقراءة فقط float.

**الإرجاع:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

يرجع عرض الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

يرجع ارتفاع الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

يرجع عدد الدرجات التي يدور فيها الإطار حول محور Z. القيمة الموجبة تشير إلى دوران عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس عقارب الساعة. للقراءة فقط float.

**الإرجاع:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

يرجع إحداثي X لمركز الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

يرجع إحداثي Y لمركز الإطار. للقراءة فقط float.

**الإرجاع:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

يحدد ما إذا كان الإطار مقلوبًا أفقيًا. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

يحدد ما إذا كان الإطار مقلوبًا عموديًا. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```

يرجع إحداثيات الإطار. للقراءة فقط java.awt.geom.Rectangle2D.Float.

**الإرجاع:**
java.awt.geom.Rectangle2D.Float