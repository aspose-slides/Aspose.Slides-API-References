---
title: IReflectionEffectiveData
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء غیرقابل تغییر که اثر بازتاب را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ireflectioneffectivedata/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)  
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

شیء غیرقابل تغییر که اثر بازتاب را نشان می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | موقعیت شروع (در طول مسیر گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. |
| [getEndPosAlpha()](#getEndPosAlpha--) | موقعیت پایان (در طول مسیر گرادیان آلفا) مقدار آلفای پایان (درصد) را مشخص می‌کند. |
| [getFadeDirection()](#getFadeDirection--) | جهت جابجایی بازتاب را مشخص می‌کند. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | شفافیت شروع بازتاب. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | شفافیت پایان بازتاب. |
| [getBlurRadius()](#getBlurRadius--) | شعاع تاری. |
| [getDirection()](#getDirection--) | جهت بازتاب. |
| [getDistance()](#getDistance--) | فاصله بازتاب. |
| [getRectangleAlign()](#getRectangleAlign--) | هم‌تراز مستطیل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | زاویه کج شدن افقی را مشخص می‌کند. |
| [getSkewVertical()](#getSkewVertical--) | زاویه کج شدن عمودی را مشخص می‌کند. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | آیا بازتاب باید هنگام چرخش شکل، همراه با شکل بچرخد یا نه، را مشخص می‌کند. |
| [getScaleHorizontal()](#getScaleHorizontal--) | فاکتور مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. |
| [getScaleVertical()](#getScaleVertical--) | فاکتور مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

موقعیت شروع (در طول مسیر گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. فقط خواندنی float.

**باز می‌گرداند:**  
float

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

موقعیت پایان (در طول مسیر گرادیان آلفا) مقدار آلفای پایان (درصد) را مشخص می‌کند. فقط خواندنی float.

**باز می‌گرداند:**  
float

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

جهت جابجایی بازتاب را مشخص می‌کند (زاویه). فقط خواندنی float.

**باز می‌گرداند:**  
float

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

شفافیت شروع بازتاب (درصد). فقط خواندنی float.

**باز می‌گرداند:**  
float

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

شفافیت پایان بازتاب (درصد). فقط خواندنی float.

**باز می‌گرداند:**  
float

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

شعاع تاری. فقط خواندنی double.

**باز می‌گرداند:**  
double

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

جهت بازتاب. فقط خواندنی float.

**باز می‌گرداند:**  
float

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

فاصله بازتاب. فقط خواندنی double.

**باز می‌گرداند:**  
double

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

هم‌تراز مستطیل. فقط خواندنی [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**باز می‌گرداند:**  
byte

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

زاویه کج شدن افقی را مشخص می‌کند. فقط خواندنی double.

**باز می‌گرداند:**  
double

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

زاویه کج شدن عمودی را مشخص می‌کند. فقط خواندنی double.

**باز می‌گرداند:**  
double

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

مشخص می‌کند آیا بازتاب باید هنگام چرخش شکل، همراه با شکل بچرخد یا نه، را. فقط خواندنی boolean.

**باز می‌گرداند:**  
boolean

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

فاکتور مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود (درصد). فقط خواندنی double.

**باز می‌گرداند:**  
double

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

فاکتور مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود (درصد). فقط خواندنی double.

**باز می‌گرداند:**  
double