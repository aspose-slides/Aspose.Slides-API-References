---
title: IMathGroupingCharacter
second_title: مرجع API Aspose.Slides برای جاوا
description: یک نماد گروه‌بندی را بالای یا زیر یک عبارت مشخص می‌کند که معمولاً برای برجسته کردن رابطه بین عناصر استفاده می‌شود
type: docs
url: /fa/com.aspose.slides/imathgroupingcharacter/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

یک نماد گروه‌بندی بالای یا زیر یک عبارت را مشخص می‌کند که معمولاً برای برجسته کردن رابطه بین عناصر استفاده می‌شود

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getCharacter()](#getCharacter--) | کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | موقعیت کاراکتر گروه‌بندی. |
| [setPosition(int value)](#setPosition-int-) | موقعیت کاراکتر گروه‌بندی. |
| [getVerticalJustification()](#getVerticalJustification--) | تراز عمودی کاراکتر گروه. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | تراز عمودی کاراکتر گروه. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**بازگشت:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // پرانتز پایین
> ```

**بازگشت:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // پرانتز پایین
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موقعیت کاراکتر گروه‌بندی. پیش‌فرض: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**بازگشت:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موقعیت کاراکتر گروه‌بندی. پیش‌فرض: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

تراز عمودی کاراکتر گروه. مشخص می‌کند که شیء نسبت به خط پایه چگونه هم‌راست می‌شود. به عنوان مثال، وقتی کاراکتر گروه در بالای شیء باشد، تراز عمودی Top به این معناست که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی تراز عمودی بر روی Bottom تنظیم شود، پایین شیء بر روی خط پایه است. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**بازگشت:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

تراز عمودی کاراکتر گروه. مشخص می‌کند که شیء نسبت به خط پایه چگونه هم‌راست می‌شود. به عنوان مثال، وقتی کاراکتر گروه در بالای شیء باشد، تراز عمودی Top به این معناست که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی تراز عمودی بر روی Bottom تنظیم شود، پایین شیء بر روی خط پایه است. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |