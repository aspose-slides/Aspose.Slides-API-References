---
title: IOuterShadow
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک افکت سایه بیرونی است.
type: docs
url: /fa/com.aspose.slides/ioutershadow/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

نمایانگر یک افکت سایه بیرونی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | شعاع تاری، به نقطه. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | شعاع تاری، به نقطه. |
| [getDirection()](#getDirection--) | جهت سایه، به درجه. |
| [setDirection(float value)](#setDirection-float-) | جهت سایه، به درجه. |
| [getDistance()](#getDistance--) | فاصله سایه از شیء، به نقطه. |
| [setDistance(double value)](#setDistance-double-) | فاصله سایه از شیء، به نقطه. |
| [getShadowColor()](#getShadowColor--) | رنگ سایه. |
| [getRectangleAlign()](#getRectangleAlign--) | تراز مستطیل. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | تراز مستطیل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | زاویه چرخش افقی، به درجه. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | زاویه چرخش افقی، به درجه. |
| [getSkewVertical()](#getSkewVertical--) | زاویه چرخش عمودی، به درجه. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | زاویه چرخش عمودی، به درجه. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | نشان می‌دهد که سایه همراه با شکل می‌چرخد یا خیر. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | نشان می‌دهد که سایه همراه با شکل می‌چرخد یا خیر. |
| [getScaleHorizontal()](#getScaleHorizontal--) | عامل مقیاس‌گذاری افقی، به درصد اندازه اصلی. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | عامل مقیاس‌گذاری افقی، به درصد اندازه اصلی. |
| [getScaleVertical()](#getScaleVertical--) | عامل مقیاس‌گذاری عمودی، به درصد اندازه اصلی. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | عامل مقیاس‌گذاری عمودی، به درصد اندازه اصلی. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

شعاع تاری، به نقطه. مقدار پیش‌فرض - 0 pt. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

شعاع تاری، به نقطه. مقدار پیش‌فرض - 0 pt. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

جهت سایه، به درجه. مقدار پیش‌فرض - 0 � (چپ به راست). قابل خواندن/نوشتن float.

**بازگشت:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

جهت سایه، به درجه. مقدار پیش‌فرض - 0 � (چپ به راست). قابل خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

فاصله سایه از شیء، به نقطه. مقدار پیش‌فرض - 0 pt. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

فاصله سایه از شیء، به نقطه. مقدار پیش‌فرض - 0 pt. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

رنگ سایه. مقدار پیش‌فرض - سیاه خودکار (وابسته به قالب). فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

تراز مستطیل. مقدار پیش‌فرض - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). قابل خواندن/نوشتن [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**بازگشت:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

تراز مستطیل. مقدار پیش‌فرض - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). قابل خواندن/نوشتن [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

زاویه چرخش افقی، به درجه. مقدار پیش‌فرض - 0 �. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

زاویه چرخش افقی، به درجه. مقدار پیش‌فرض - 0 �. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

زاویه چرخش عمودی، به درجه. مقدار پیش‌فرض - 0 �. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

زاویه چرخش عمودی، به درجه. مقدار پیش‌فرض - 0 �. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

نشان می‌دهد که سایه همراه با شکل می‌چرخد یا خیر. مقدار پیش‌فرض - true. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

نشان می‌دهد که سایه همراه با شکل می‌چرخد یا خیر. مقدار پیش‌فرض - true. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

عامل مقیاس‌گذاری افقی، به درصد اندازه اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - 100 %. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

عامل مقیاس‌گذاری افقی، به درصد اندازه اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - 100 %. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

عامل مقیاس‌گذاری عمودی، به درصد اندازه اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - 100 %. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

عامل مقیاس‌گذاری عمودی، به درصد اندازه اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - 100 %. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |