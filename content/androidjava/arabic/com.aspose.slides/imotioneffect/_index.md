---
title: IMotionEffect
second_title: Aspose.Slides for Android عبر مرجع API جافا
description: تمثّل سلوك تأثير الحركة للتأثير.
type: docs
url: /ar/com.aspose.slides/imotioneffect/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

يمثل سلوك تأثير الحركة للتأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFrom()](#getFrom--) | يحدد إحداثي x/y لبدء الرسوم المتحركة من (بالنسبة المئوية). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | يحدد إحداثي x/y لبدء الرسوم المتحركة من (بالنسبة المئوية). |
| [getTo()](#getTo--) | يحدد الموقع المستهدف لتأثير حركة الرسوم المتحركة (بالنسبة المئوية). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | يحدد الموقع المستهدف لتأثير حركة الرسوم المتحركة (بالنسبة المئوية). |
| [getBy()](#getBy--) | يصف قيمة الإزاحة النسبية للرسوم المتحركة (بالنسبة المئوية). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | يصف قيمة الإزاحة النسبية للرسوم المتحركة (بالنسبة المئوية). |
| [getRotationCenter()](#getRotationCenter--) | يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. |
| [getOrigin()](#getOrigin--) | يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. |
| [setOrigin(int value)](#setOrigin-int-) | يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. |
| [getPath()](#getPath--) | يحدد البدائي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | يحدد البدائي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. |
| [getPathEditMode()](#getPathEditMode--) | يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. |
| [getAngle()](#getAngle--) | يصف الزاوية النسبية لمسار الحركة. |
| [setAngle(float value)](#setAngle-float-) | يصف الزاوية النسبية لمسار الحركة. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

يحدد إحداثي x/y لبدء الرسوم المتحركة من (بالنسبة المئوية). Read/write android.graphics.PointF.

**القيمة المرتجعة:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

يحدد إحداثي x/y لبدء الرسوم المتحركة من (بالنسبة المئوية). Read/write android.graphics.PointF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```

يحدد الموقع المستهدف لتأثير حركة الرسوم المتحركة (بالنسبة المئوية). Read/write android.graphics.PointF.

**القيمة المرتجعة:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

يحدد الموقع المستهدف لتأثير حركة الرسوم المتحركة (بالنسبة المئوية). Read/write android.graphics.PointF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```

يصف قيمة الإزاحة النسبية للرسوم المتحركة (بالنسبة المئوية). Read/write android.graphics.PointF.

**القيمة المرتجعة:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

يصف قيمة الإزاحة النسبية للرسوم المتحركة (بالنسبة المئوية). Read/write android.graphics.PointF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. Read/write android.graphics.PointF.

**القيمة المرتجعة:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

يصف مركز الدوران المستخدم لتدوير مسار الحركة بزاوية X. Read/write android.graphics.PointF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. Read/write [MotionOriginType](../../com.aspose.slides/motionorigintype).

**القيمة المرتجعة:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

يحدد ما هو أصل مسار الحركة بالنسبة إلى مثل تخطيط الشريحة أو العنصر الأب. Read/write [MotionOriginType](../../com.aspose.slides/motionorigintype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

يحدد البدائي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. Read/write [IMotionPath](../../com.aspose.slides/imotionpath).

**القيمة المرتجعة:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

يحدد البدائي للمسار متبوعًا بالإحداثيات لحركة الرسوم المتحركة. Read/write [IMotionPath](../../com.aspose.slides/imotionpath).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. Read/write [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**القيمة المرتجعة:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

يحدد كيفية تحرك مسار الحركة عندما يتم نقل الشكل. Read/write [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

يصف الزاوية النسبية لمسار الحركة. Read/write float.

**القيمة المرتجعة:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

يصف الزاوية النسبية لمسار الحركة. Read/write float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |