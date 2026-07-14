---
title: MathBorderBox
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: یک مرز مستطیلی یا مرز دیگری را دور IMathElement می‌کشد.
type: docs
url: /fa/com.aspose.slides/mathborderbox/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

یک مرز مستطیلی یا مرز دیگری را دور IMathElement می‌کشد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | یک عنصر MathBorderBox با مرز مستطیلی ایجاد می‌کند |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | یک عنصر MathBorderBox ایجاد می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getHideTop()](#getHideTop--) | پنهان کردن لبه بالایی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه بالایی جعبه مرز را مشخص می‌کند. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | پنهان کردن لبه بالایی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه بالایی جعبه مرز را مشخص می‌کند. |
| [getHideBottom()](#getHideBottom--) | پنهان کردن لبه پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه پایین جعبه مرز را مشخص می‌کند. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | پنهان کردن لبه پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه پایین جعبه مرز را مشخص می‌کند. |
| [getHideLeft()](#getHideLeft--) | پنهان کردن لبه چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه چپ جعبه مرز را مشخص می‌کند. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | پنهان کردن لبه چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه چپ جعبه مرز را مشخص می‌کند. |
| [getHideRight()](#getHideRight--) | پنهان کردن لبه راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه راست جعبه مرز را مشخص می‌کند. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | پنهان کردن لبه راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه راست جعبه مرز را مشخص می‌کند. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | خط‌کش افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش افقی را مشخص می‌کند. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | خط‌کش افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش افقی را مشخص می‌کند. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | خط‌کش عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش عمودی را مشخص می‌کند. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | خط‌کش عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش عمودی را مشخص می‌کند. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | خط‌کش از پایین-چپ به بالا-راست (پیش‌فرض false است). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | خط‌کش از پایین-چپ به بالا-راست (پیش‌فرض false است). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | خط‌کش از بالا-چپ به پایین-راست (پیش‌فرض false است). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | خط‌کش از بالا-چپ به پایین-راست (پیش‌فرض false است). |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

یک عنصر MathBorderBox با مرز مستطیلی ایجاد می‌کند

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که جعبه مرز به آن اعمال می‌شود. می‌تواند null باشد. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

یک عنصر MathBorderBox ایجاد می‌کند

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که جعبه مرز به آن اعمال می‌شود |
| hideTop | boolean | پنهان کردن لبه بالایی |
| hideBottom | boolean | پنهان کردن لبه پایین |
| hideLeft | boolean | پنهان کردن لبه چپ |
| hideRight | boolean | پنهان کردن لبه راست |
| strikethroughHorizontal | boolean | خط‌کش افقی |
| strikethroughVertical | boolean | خط‌کش عمودی |
| strikethroughBottomLeftToTopRight | boolean | خط‌کش از پایین-چپ به بالا-راست |
| strikethroughTopLeftToBottomRight | boolean | خط‌کش از بالا-چپ به پایین-راست |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**باز می‌گردد:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

پنهان کردن لبه بالایی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه بالایی جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**باز می‌گردد:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

پنهان کردن لبه بالایی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه بالایی جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

پنهان کردن لبه پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه پایین جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**باز می‌گردد:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

پنهان کردن لبه پایین (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه پایین جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

پنهان کردن لبه چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه چپ جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**باز می‌گردد:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

پنهان کردن لبه چپ (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه چپ جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

پنهان کردن لبه راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه راست جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**باز می‌گردد:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

پنهان کردن لبه راست (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده لبه راست جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

خط‌کش افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش افقی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**باز می‌گردد:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

خط‌کش افقی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش افقی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

خط‌کش عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش عمودی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**باز می‌گردد:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

خط‌کش عمودی (پیش‌فرض false است) - وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش عمودی را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

خط‌کش از پایین-چپ به بالا-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش قطره‌ای از گوشه پایین-چپ به گوشه بالا-راست جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**باز می‌گردد:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

خط‌کش از پایین-چپ به بالا-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش قطره‌ای از گوشه پایین-چپ به گوشه بالا-راست جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

خط‌کش از بالا-چپ به پایین-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش قطره‌ای از گوشه بالا-چپ به گوشه پایین-راست جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**باز می‌گردد:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

خط‌کش از بالا-چپ به پایین-راست (پیش‌فرض false است). وضعیت مخفی یا نمایش‌داده‌شده یک خط‌کش قطره‌ای از گوشه بالا-چپ به گوشه پایین-راست جعبه مرز را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**باز می‌گردد:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترل

**باز می‌گردد:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps