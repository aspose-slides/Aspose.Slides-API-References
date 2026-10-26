---
title: IMathBorderBox
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک مرز مستطیلی یا نوع دیگری را دور IMathElement می‌کشد.
type: docs
url: /fa/com.aspose.slides/imathborderbox/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

یک مرز مستطیلی یا نوع دیگری را دور **IMathElement** می‌کشد.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getHideTop()](#getHideTop--) | پنهان کردن لبهٔ بالا (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرز را مشخص می‌کند. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | پنهان کردن لبهٔ بالا (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرز را مشخص می‌کند. |
| [getHideBottom()](#getHideBottom--) | پنهان کردن لبهٔ پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرز را مشخص می‌کند. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | پنهان کردن لبهٔ پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرز را مشخص می‌کند. |
| [getHideLeft()](#getHideLeft--) | پنهان کردن لبهٔ چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرز را مشخص می‌کند. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | پنهان کردن لبهٔ چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرز را مشخص می‌کند. |
| [getHideRight()](#getHideRight--) | پنهان کردن لبهٔ راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرز را مشخص می‌کند. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | پنهان کردن لبهٔ راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرز را مشخص می‌کند. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | خط خوردهٔ افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ افقی را مشخص می‌کند. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | خط خوردهٔ افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ افقی را مشخص می‌کند. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | خط خوردهٔ عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ عمودی را مشخص می‌کند. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | خط خوردهٔ عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ عمودی را مشخص می‌کند. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | خط خوردهٔ قطر از پایین-چپ به بالا-راست (پیش‌فرض false است). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | خط خوردهٔ قطر از پایین-چپ به بالا-راست (پیش‌فرض false است). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | خط خوردهٔ قطر از بالا-چپ به پایین-راست (پیش‌فرض false است). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | خط خوردهٔ قطر از بالا-چپ به پایین-راست (پیش‌فرض false است). |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```


**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)

### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

پنهان کردن لبهٔ بالا (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**بازگشت:**  
boolean

### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

پنهان کردن لبهٔ بالا (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

پنهان کردن لبهٔ پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**بازگشت:**  
boolean

### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

پنهان کردن لبهٔ پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

پنهان کردن لبهٔ چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**بازگشت:**  
boolean

### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

پنهان کردن لبهٔ چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

پنهان کردن لبهٔ راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**بازگشت:**  
boolean

### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

پنهان کردن لبهٔ راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

خط خوردهٔ افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ افقی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**بازگشت:**  
boolean

### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

خط خوردهٔ افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ افقی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

خط خوردهٔ عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ عمودی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**بازگشت:**  
boolean

### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

خط خوردهٔ عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ عمودی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

خط خوردهٔ قطر از پایین-چپ به بالا-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ قطر از گوشهٔ پایین-چپ به گوشهٔ بالا-راست جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**بازگشت:**  
boolean

### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

خط خوردهٔ قطر از پایین-چپ به بالا-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ قطر از گوشهٔ پایین-چپ به گوشهٔ بالا-راست جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

خط خوردهٔ قطر از بالا-چپ به پایین-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ قطر از گوشهٔ بالا-چپ به گوشهٔ پایین-راست جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**بازگشت:**  
boolean

### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

خط خوردهٔ قطر از بالا-چپ به پایین-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط خوردهٔ قطر از گوشهٔ بالا-چپ به گوشهٔ پایین-راست جعبهٔ مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |