---
title: IMotionEffect
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش رفتار اثر حرکتی.
type: docs
url: /fa/com.aspose.slides/imotioneffect/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

نمایش رفتار اثر حرکتی.

## متدها

| متد | توضیح |
| --- | --- |
| [getFrom()](#getFrom--) | مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). |
| [getTo()](#getTo--) | مکان هدف برای اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | مکان هدف برای اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). |
| [getBy()](#getBy--) | مقدار جابجایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | مقدار جابجایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). |
| [getRotationCenter()](#getRotationCenter--) | مرکز چرخش استفاده شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | مرکز چرخش استفاده شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. |
| [getOrigin()](#getOrigin--) | مشخص می‌کند مبدأ مسیر حرکت نسبت به چه چیزی است، مانند طرح اسلاید یا والد. |
| [setOrigin(int value)](#setOrigin-int-) | مشخص می‌کند مبدأ مسیر حرکت نسبت به چه چیزی است، مانند طرح اسلاید یا والد. |
| [getPath()](#getPath--) | پرایمیتوی مسیر را به‌همراه مختصات برای حرکت انیمیشن مشخص می‌کند. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | پرایمیتوی مسیر را به‌همراه مختصات برای حرکت انیمیشن مشخص می‌کند. |
| [getPathEditMode()](#getPathEditMode--) | نحوه حرکت مسیر حرکت هنگام جابه‌جایی شکل را مشخص می‌کند. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | نحوه حرکت مسیر حرکت هنگام جابه‌جایی شکل را مشخص می‌کند. |
| [getAngle()](#getAngle--) | زاویۀ نسبی مسیر حرکت را توصیف می‌کند. |
| [setAngle(float value)](#setAngle-float-) | زاویۀ نسبی مسیر حرکت را توصیف می‌کند. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). خواندنی/قابل نوشتن android.graphics.PointF.

**بازگرداندن:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

مختصات x/y را برای شروع انیمیشن مشخص می‌کند (به درصد). خواندنی/قابل نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

مکان هدف برای اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). خواندنی/قابل نوشتن android.graphics.PointF.

**بازگرداندن:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

مکان هدف برای اثر حرکتی انیمیشن را مشخص می‌کند (به درصد). خواندنی/قابل نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

مقدار جابجایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). خواندنی/قابل نوشتن android.graphics.PointF.

**بازگرداندن:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

مقدار جابجایی نسبی برای انیمیشن را توصیف می‌کند (به درصد). خواندنی/قابل نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

مرکز چرخش استفاده شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. خواندنی/قابل نوشتن android.graphics.PointF.

**بازگرداندن:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

مرکز چرخش استفاده شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. خواندنی/قابل نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

مشخص می‌کند مبدأ مسیر حرکت نسبت به چه چیزی است، مانند طرح اسلاید یا والد. خواندنی/قابل نوشتن [MotionOriginType](../../com.aspose.slides/motionorigintype).

**بازگرداندن:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

مشخص می‌کند مبدأ مسیر حرکت نسبت به چه چیزی است، مانند طرح اسلاید یا والد. خواندنی/قابل نوشتن [MotionOriginType](../../com.aspose.slides/motionorigintype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

پرایمیتوی مسیر را به‌همراه مختصات برای حرکت انیمیشن مشخص می‌کند. خواندنی/قابل نوشتن [IMotionPath](../../com.aspose.slides/imotionpath).

**بازگرداندن:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

پرایمیتوی مسیر را به‌همراه مختصات برای حرکت انیمیشن مشخص می‌کند. خواندنی/قابل نوشتن [IMotionPath](../../com.aspose.slides/imotionpath).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

نحوه حرکت مسیر حرکت هنگام جابه‌جایی شکل را مشخص می‌کند. خواندنی/قابل نوشتن [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**بازگرداندن:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

نحوه حرکت مسیر حرکت هنگام جابه‌جایی شکل را مشخص می‌کند. خواندنی/قابل نوشتن [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

زاویۀ نسبی مسیر حرکت را توصیف می‌کند. خواندنی/قابل نوشتن float.

**بازگرداندن:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

زاویۀ نسبی مسیر حرکت را توصیف می‌کند. خواندنی/قابل نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |