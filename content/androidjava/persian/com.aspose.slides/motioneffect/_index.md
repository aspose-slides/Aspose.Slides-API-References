---
title: MotionEffect
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: رفتار اثر حرکتی را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/motioneffect/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

رفتار اثر حرکتی را نشان می‌دهد.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## متدها

| متد | توضیح |
| --- | --- |
| [getFrom()](#getFrom--) | مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). |
| [getTo()](#getTo--) | موقعیت هدف برای یک اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | موقعیت هدف برای یک اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). |
| [getBy()](#getBy--) | مقدار جابه‌جایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | مقدار جابه‌جایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). |
| [getRotationCenter()](#getRotationCenter--) | مرکز چرخش مورد استفاده برای چرخاندن مسیر حرکتی به زاویه X را توصیف می‌کند. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | مرکز چرخش مورد استفاده برای چرخاندن مسیر حرکتی به زاویه X را توصیف می‌کند. |
| [getOrigin()](#getOrigin--) | مشخص می‌کند منبع مسیر حرکتی نسبت به چه چیزی است، مانند چیدمان اسلاید یا والد. |
| [setOrigin(int value)](#setOrigin-int-) | مشخص می‌کند منبع مسیر حرکتی نسبت به چه چیزی است، مانند چیدمان اسلاید یا والد. |
| [getPath()](#getPath--) | مسیر اولیه را به همراه مختصات برای حرکت انیمیشن مشخص می‌کند. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | مسیر اولیه را به همراه مختصات برای حرکت انیمیشن مشخص می‌کند. |
| [getPathEditMode()](#getPathEditMode--) | نحوه حرکت مسیر حرکتی هنگام جابجایی شکل را مشخص می‌کند. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | نحوه حرکت مسیر حرکتی هنگام جابجایی شکل را مشخص می‌کند. |
| [getAngle()](#getAngle--) | زاویه نسبی مسیر حرکتی را توصیف می‌کند. |
| [setAngle(float value)](#setAngle-float-) | زاویه نسبی مسیر حرکتی را توصیف می‌کند. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). خواندن/نوشتن android.graphics.PointF.

**بازمی‌گردد:**  
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). خواندن/نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

موقعیت هدف برای یک اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). خواندن/نوشتن android.graphics.PointF.

**بازمی‌گردد:**  
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

موقعیت هدف برای یک اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). خواندن/نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

مقدار جابه‌جایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). خواندن/نوشتن android.graphics.PointF.

**بازمی‌گردد:**  
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

مقدار جابه‌جایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). خواندن/نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

مرکز چرخش مورد استفاده برای چرخاندن مسیر حرکتی به زاویه X را توصیف می‌کند. خواندن/نوشتن android.graphics.PointF.

**بازمی‌گردد:**  
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

مرکز چرخش مورد استفاده برای چرخاندن مسیر حرکتی به زاویه X را توصیف می‌کند. خواندن/نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

مشخص می‌کند منبع مسیر حرکتی نسبت به چه چیزی است، مانند چیدمان اسلاید یا والد. خواندن/نوشتن [MotionOriginType](../../com.aspose.slides/motionorigintype).

**بازمی‌گردد:**  
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

مشخص می‌کند منبع مسیر حرکتی نسبت به چه چیزی است، مانند چیدمان اسلاید یا والد. خواندن/نوشتن [MotionOriginType](../../com.aspose.slides/motionorigintype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

مسیر اولیه را به همراه مختصات برای حرکت انیمیشن مشخص می‌کند. خواندن/نوشتن [IMotionPath](../../com.aspose.slides/imotionpath).

**بازمی‌گردد:**  
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

مسیر اولیه را به همراه مختصات برای حرکت انیمیشن مشخص می‌کند. خواندن/نوشتن [IMotionPath](../../com.aspose.slides/imotionpath).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

نحوه حرکت مسیر حرکتی هنگام جابجایی شکل را مشخص می‌کند. خواندن/نوشتن [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**بازمی‌گردد:**  
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

نحوه حرکت مسیر حرکتی هنگام جابجایی شکل را مشخص می‌کند. خواندن/نوشتن [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

زاویه نسبی مسیر حرکتی را توصیف می‌کند. خواندن/نوشتن float.

**بازمی‌گردد:**  
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

زاویه نسبی مسیر حرکتی را توصیف می‌کند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |