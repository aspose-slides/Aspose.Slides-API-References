---
title: IMotionEffect
second_title: مرجع API Aspose.Slides for Java
description: تمثيل سلوك تأثير الحركة للتأثير.
type: docs
url: /ar/com.aspose.slides/imotioneffect/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

يمثل سلوك تأثير الحركة للتأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFrom()](#getFrom--) | يحدد إحداثي x/y لبدء الرسوم المتحركة من (نسبة مئوية). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | يحدد إحداثي x/y لبدء الرسوم المتحركة من (نسبة مئوية). |
| [getTo()](#getTo--) | يحدد الموقع الهدف لتأثير حركة الرسوم المتحركة (نسبة مئوية). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | يحدد الموقع الهدف لتأثير حركة الرسوم المتحركة (نسبة مئوية). |
| [getBy()](#getBy--) | وصف القيمة النسبية للإزاحة للرسوم المتحركة (نسبة مئوية). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | وصف القيمة النسبية للإزاحة للرسوم المتحركة (نسبة مئوية). |
| [getRotationCenter()](#getRotationCenter--) | يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. |
| [getOrigin()](#getOrigin--) | يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. |
| [setOrigin(int value)](#setOrigin-int-) | يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. |
| [getPath()](#getPath--) | يحدد الشكل الأساسي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | يحدد الشكل الأساسي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. |
| [getPathEditMode()](#getPathEditMode--) | يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. |
| [getAngle()](#getAngle--) | وصف الزاوية النسبية لمسار الحركة. |
| [setAngle(float value)](#setAngle-float-) | وصف الزاوية النسبية لمسار الحركة. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

يحدد إحداثي x/y لبدء الرسوم المتحركة من (نسبة مئوية). قراءة/كتابة java.awt.geom.Point2D.Float.

**القيمة المرتجعة:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

يحدد إحداثي x/y لبدء الرسوم المتحركة من (نسبة مئوية). قراءة/كتابة java.awt.geom.Point2D.Float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

يحدد الموقع الهدف لتأثير حركة الرسوم المتحركة (نسبة مئوية). قراءة/كتابة java.awt.geom.Point2D.Float.

**القيمة المرتجعة:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

يحدد الموقع الهدف لتأثير حركة الرسوم المتحركة (نسبة مئوية). قراءة/كتابة java.awt.geom.Point2D.Float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

وصف القيمة النسبية للإزاحة للرسوم المتحركة (نسبة مئوية). قراءة/كتابة java.awt.geom.Point2D.Float.

**القيمة المرتجعة:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

وصف القيمة النسبية للإزاحة للرسوم المتحركة (نسبة مئوية). قراءة/كتابة java.awt.geom.Point2D.Float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. قراءة/كتابة java.awt.geom.Point2D.Float.

**القيمة المرتجعة:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. قراءة/كتابة java.awt.geom.Point2D.Float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. قراءة/كتابة [MotionOriginType](../../com.aspose.slides/motionorigintype).

**القيمة المرتجعة:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. قراءة/كتابة [MotionOriginType](../../com.aspose.slides/motionorigintype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

يحدد الشكل الأساسي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. قراءة/كتابة [IMotionPath](../../com.aspose.slides/imotionpath).

**القيمة المرتجعة:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

يحدد الشكل الأساسي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. قراءة/كتابة [IMotionPath](../../com.aspose.slides/imotionpath).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. قراءة/كتابة [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**القيمة المرتجعة:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. قراءة/كتابة [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

وصف الزاوية النسبية لمسار الحركة. قراءة/كتابة float.

**القيمة المرتجعة:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

وصف الزاوية النسبية لمسار الحركة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |