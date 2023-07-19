---
title: MotionEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represent motion effect behavior of effect.
type: docs
weight: 371
url: /androidjava/com.aspose.slides/motioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**All Implemented Interfaces:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Represent motion effect behavior of effect.
## Constructors

| Constructor | Description |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Specifies an x/y co-ordinate to start the animation from (in percents). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Specifies an x/y co-ordinate to start the animation from (in percents). |
| [getTo()](#getTo--) | Specifies the target location for an animation motion effect (in percents). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Specifies the target location for an animation motion effect (in percents). |
| [getBy()](#getBy--) | Describes the relative offset value for the animation (in percents). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Describes the relative offset value for the animation (in percents). |
| [getRotationCenter()](#getRotationCenter--) | Describes the center of the rotation used to rotate a motion path by X angle. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Describes the center of the rotation used to rotate a motion path by X angle. |
| [getOrigin()](#getOrigin--) | Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. |
| [setOrigin(int value)](#setOrigin-int-) | Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. |
| [getPath()](#getPath--) | Specifies the path primitive followed by coordinates for the animation motion. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specifies the path primitive followed by coordinates for the animation motion. |
| [getPathEditMode()](#getPathEditMode--) | Specifies how the motion path moves when shape is moved. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specifies how the motion path moves when shape is moved. |
| [getAngle()](#getAngle--) | Describes the relative angle of the motion path. |
| [setAngle(float value)](#setAngle-float-) | Describes the relative angle of the motion path. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


Specifies an x/y co-ordinate to start the animation from (in percents). Read/write android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


Specifies an x/y co-ordinate to start the animation from (in percents). Read/write android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


Specifies the target location for an animation motion effect (in percents). Read/write android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


Specifies the target location for an animation motion effect (in percents). Read/write android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


Describes the relative offset value for the animation (in percents). Read/write android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


Describes the relative offset value for the animation (in percents). Read/write android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


Describes the center of the rotation used to rotate a motion path by X angle. Read/write android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


Describes the center of the rotation used to rotate a motion path by X angle. Read/write android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. Read/write [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Returns:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. Read/write [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Specifies the path primitive followed by coordinates for the animation motion. Read/write [IMotionPath](../../com.aspose.slides/imotionpath).

**Returns:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Specifies the path primitive followed by coordinates for the animation motion. Read/write [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Specifies how the motion path moves when shape is moved. Read/write [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Returns:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Specifies how the motion path moves when shape is moved. Read/write [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Describes the relative angle of the motion path. Read/write float.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Describes the relative angle of the motion path. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

