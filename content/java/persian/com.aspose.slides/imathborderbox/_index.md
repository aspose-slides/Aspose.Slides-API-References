---
title: IMathBorderBox
second_title: Aspose.Slides برای مرجع API جاوا
description: یک حاشیه مستطیلی یا نوع دیگری را اطراف IMathElement می‌کشد.
type: docs
url: /fa/com.aspose.slides/imathborderbox/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

یک حاشیه مستطیلی یا نوع دیگری از حاشیه را اطراف IMathElement می‌کشد.

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
| [getHideTop()](#getHideTop--) | مخفی‌سازی لبهٔ بالایی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرزی را مشخص می‌کند. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | مخفی‌سازی لبهٔ بالایی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرزی را مشخص می‌کند. |
| [getHideBottom()](#getHideBottom--) | مخفی‌سازی لبهٔ پایین (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرزی را مشخص می‌کند. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | مخفی‌سازی لبهٔ پایین (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرزی را مشخص می‌کند. |
| [getHideLeft()](#getHideLeft--) | مخفی‌سازی لبهٔ چپ (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرزی را مشخص می‌کند. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | مخفی‌سازی لبهٔ چپ (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرزی را مشخص می‌کند. |
| [getHideRight()](#getHideRight--) | مخفی‌سازی لبهٔ راست (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرزی را مشخص می‌کند. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | مخفی‌سازی لبهٔ راست (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرزی را مشخص می‌کند. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | خط‌دار افقی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار افقی را مشخص می‌کند. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | خط‌دار افقی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار افقی را مشخص می‌کند. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | خط‌دار عمودی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار عمودی را مشخص می‌کند. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | خط‌دار عمودی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار عمودی را مشخص می‌کند. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | خط‌دار از پایین-چپ به بالا-راست (به‌صورت پیش‌فرض false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | خط‌دار از پایین-چپ به بالا-راست (به‌صورت پیش‌فرض false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | خط‌دار از بالا-چپ به پایین-راست (به‌صورت پیش‌فرض false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | خط‌دار از بالا-چپ به پایین-راست (به‌صورت پیش‌فرض false). |

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

مخفی‌سازی لبهٔ بالایی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ بالایی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ بالایی جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ پایین (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ پایین (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ پایین جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ چپ (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ چپ (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ چپ جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ راست (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرزی را مشخص می‌کند.

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

مخفی‌سازی لبهٔ راست (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ لبهٔ راست جعبهٔ مرزی را مشخص می‌کند.

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

خط‌دار افقی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار افقی را مشخص می‌کند.

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

خط‌دار افقی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار افقی را مشخص می‌کند.

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

خط‌دار عمودی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار عمودی را مشخص می‌کند.

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

خط‌دار عمودی (به‌صورت پیش‌فرض false) - وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار عمودی را مشخص می‌کند.

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

خط‌دار از پایین-چپ به بالا-راست (به‌صورت پیش‌فرض false). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار مورب از گوشهٔ پایین-چپ به گوشهٔ بالا-راست جعبهٔ مرزی را مشخص می‌کند.

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

خط‌دار از پایین-چپ به بالا-راست (به‌صورت پیش‌فرض false). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار مورب از گوشهٔ پایین-چپ به گوشهٔ بالا-راست جعبهٔ مرزی را مشخص می‌کند.

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

خط‌دار از بالا-چپ به پایین-راست (به‌صورت پیش‌فرض false). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار مورب از گوشهٔ بالا-چپ به گوشهٔ پایین-راست جعبهٔ مرزی را مشخص می‌کند.

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

خط‌دار از بالا-چپ به پایین-راست (به‌صورت پیش‌فرض false). وضعیت مخفی یا نمایش‌داده‌شدهٔ یک خط‌دار مورب از گوشهٔ بالا-چپ به گوشهٔ پایین-راست جعبهٔ مرزی را مشخص می‌کند.

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