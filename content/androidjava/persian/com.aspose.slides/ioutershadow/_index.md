---
title: IOuterShadow
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک افکت سایهٔ خارجی است.
type: docs
url: /fa/com.aspose.slides/ioutershadow/
---
**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

نمایانگر یک افکت سایهٔ خارجی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | شعاع محو شدن، بر حسب نقطه. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | شعاع محو شدن، بر حسب نقطه. |
| [getDirection()](#getDirection--) | جهت سایه، بر حسب درجه. |
| [setDirection(float value)](#setDirection-float-) | جهت سایه، بر حسب درجه. |
| [getDistance()](#getDistance--) | فاصله سایه از شی، بر حسب نقطه. |
| [setDistance(double value)](#setDistance-double-) | فاصله سایه از شی، بر حسب نقطه. |
| [getShadowColor()](#getShadowColor--) | رنگ سایه. |
| [getRectangleAlign()](#getRectangleAlign--) | تراز مستطیل. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | تراز مستطیل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | زاویهٔ اسکِی افقی، بر حسب درجه. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | زاویهٔ اسکِی افقی، بر حسب درجه. |
| [getSkewVertical()](#getSkewVertical--) | زاویهٔ اسکِی عمودی، بر حسب درجه. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | زاویهٔ اسکِی عمودی، بر حسب درجه. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | نشان می‌دهد که آیا سایه‌ همراه شکل می‌چرخد یا نه. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | نشان می‌دهد که آیا سایه‌ همراه شکل می‌چرخد یا نه. |
| [getScaleHorizontal()](#getScaleHorizontal--) | عامل مقیاس افقی، به درصد اندازهٔ اصلی. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | عامل مقیاس افقی، به درصد اندازهٔ اصلی. |
| [getScaleVertical()](#getScaleVertical--) | عامل مقیاس عمودی، به درصد اندازهٔ اصلی. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | عامل مقیاس عمودی، به درصد اندازهٔ اصلی. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

شعاع محو شدن، بر حسب نقطه. مقدار پیش‌فرض - ۰ pt. خواندنی/نوشتنی double.

**باز می‌گردد:**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

شعاع محو شدن، بر حسب نقطه. مقدار پیش‌فرض - ۰ pt. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

جهت سایه، بر حسب درجه. مقدار پیش‌فرض - ۰ ° (چپ به راست). خواندنی/نوشتنی float.

**باز می‌گردد:**  
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

جهت سایه، بر حسب درجه. مقدار پیش‌فرض - ۰ ° (چپ به راست). خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

فاصله سایه از شی، بر حسب نقطه. مقدار پیش‌فرض - ۰ pt. خواندنی/نوشتنی double.

**باز می‌گردد:**  
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

فاصله سایه از شی، بر حسب نقطه. مقدار پیش‌فرض - ۰ pt. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

رنگ سایه. مقدار پیش‌فرض - سیاه خودکار (وابسته به تم). فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گردد:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

تراز مستطیل. مقدار پیش‌فرض - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). خواندنی/نوشتنی [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**باز می‌گردد:**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

تراز مستطیل. مقدار پیش‌فرض - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). خواندنی/نوشتنی [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

زاویهٔ اسکِی افقی، بر حسب درجه. مقدار پیش‌فرض - ۰ °. خواندنی/نوشتنی double.

**باز می‌گردد:**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

زاویهٔ اسکِی افقی، بر حسب درجه. مقدار پیش‌فرض - ۰ °. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

زاویهٔ اسکِی عمودی، بر حسب درجه. مقدار پیش‌فرض - ۰ °. خواندنی/نوشتنی double.

**باز می‌گردد:**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

زاویهٔ اسکِی عمودی، بر حسب درجه. مقدار پیش‌فرض - ۰ °. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

نشان می‌دهد که آیا سایه‌ همراه شکل می‌چرخد یا نه. مقدار پیش‌فرض - true. خواندنی/نوشتنی boolean.

**باز می‌گردد:**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

نشان می‌دهد که آیا سایه‌ همراه شکل می‌چرخد یا نه. مقدار پیش‌فرض - true. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

عامل مقیاس افقی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - ۱۰۰ ٪. خواندنی/نوشتنی double.

**باز می‌گردد:**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

عامل مقیاس افقی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - ۱۰۰ ٪. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

عامل مقیاس عمودی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - ۱۰۰ ٪. خواندنی/نوشتنی double.

**باز می‌گردد:**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

عامل مقیاس عمودی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض - ۱۰۰ ٪. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |