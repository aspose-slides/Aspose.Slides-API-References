---
title: IShapeFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثّل خصائص إطارات الشكل.
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
| [getX()](#getX--) | يرجع إحداثي X للزاوية العلوية اليسرى للإطار. |
| [getY()](#getY--) | يرجع إحداثي Y للزاوية العلوية اليسرى للإطار. |
| [getWidth()](#getWidth--) | يرجع عرض الإطار. |
| [getHeight()](#getHeight--) | يرجع ارتفاع الإطار. |
| [getRotation()](#getRotation--) | يرجع عدد الدرجات التي يتم فيها تدوير الإطار حول محور z. |
| [getCenterX()](#getCenterX--) | يرجع إحداثي X لمركز الإطار. |
| [getCenterY()](#getCenterY--) | يرجع إحداثي Y لمركز الإطار. |
| [getFlipH()](#getFlipH--) | يحدد ما إذا كان الإطار مقلوبًا أفقيًا. |
| [getFlipV()](#getFlipV--) | يحدد ما إذا كان الإطار مقلوبًا رأسيًا. |
| [getRectangle()](#getRectangle--) | يرجع إحداثيات الإطار. |
### getX() {#getX--}
```
public abstract float getX()
```

يرجع إحداثي X للزاوية العلوية اليسرى للإطار. للقراءة فقط float.

**القيمة المرجعة:**
float
### getY() {#getY--}
```
public abstract float getY()
```

يرجع إحداثي Y للزاوية العلوية اليسرى للإطار. للقراءة فقط float.

**القيمة المرجعة:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

يرجع عرض الإطار. للقراءة فقط float.

**القيمة المرجعة:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

يرجع ارتفاع الإطار. للقراءة فقط float.

**القيمة المرجعة:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

يرجع عدد الدرجات التي يتم فيها تدوير الإطار حول محور z. القيمة الموجبة تشير إلى دوران مع اتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. للقراءة فقط float.

**القيمة المرجعة:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

يرجع إحداثي X لمركز الإطار. للقراءة فقط float.

**القيمة المرجعة:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

يرجع إحداثي Y لمركز الإطار. للقراءة فقط float.

**القيمة المرجعة:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

يحدد ما إذا كان الإطار مقلوبًا أفقيًا. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

يحدد ما إذا كان الإطار مقلوبًا رأسيًا. للقراءة فقط [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

يرجع إحداثيات الإطار. للقراءة فقط android.graphics.RectF.

**القيمة المرجعة:**
android.graphics.RectF