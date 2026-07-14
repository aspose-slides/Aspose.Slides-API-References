---
title: IMathGroupingCharacter
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: نماد گروه‌بندی را بالای یا پایین یک عبارت مشخص می‌کند که معمولاً برای برجسته‌سازی رابطه بین عناصر استفاده می‌شود
type: docs
url: /fa/com.aspose.slides/imathgroupingcharacter/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

یک نماد گروه‌بندی را بالای یا پایین یک عبارت مشخص می‌کند، که معمولاً برای برجسته‌سازی رابطه بین عناصر استفاده می‌شود

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
>  ```

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


**بازگرداندن:**
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


**بازگرداندن:**
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

**بازگرداندن:**
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


تراز عمودی کاراکتر گروه. تنظیم تراز شیء نسبت به خط پایه را مشخص می‌کند. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification of Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification برابر Bottom تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**بازگرداندن:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


تراز عمودی کاراکتر گروه. تنظیم تراز شیء نسبت به خط پایه را مشخص می‌کند. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification of Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification برابر Bottom تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

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